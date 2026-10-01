# Product data architecture: the case for change

**Status.** Draft v1, 09/09/2026. Not agreed. Working document for Joe Collingwood and Michelle to
build out together before it goes to Rabbie's exec and tech leads. Also intended to be discussed at
the all agency meeting on 23 September 2026.

**Due.** 16 September 2026.

**How to use it.** The five sections below are the structure we agreed. The three problems Michelle
raised run through each section as three strands of one case, because they share a root cause. Blank
figures are marked and owned. This document deliberately does not specify a solution. That is the
technical team's to bring.

---

## The answer, up front

Rabbie's is paying twice for the same problem. The Ecommerce team pay in hours, keeping product data
correct by hand. Customers pay in wrong, missing or stale information at the exact point where about
92% of visitors are already dropping off. The three problems Michelle raised are the same problem
seen from three places.

The fix is an outcome, not a feature: product data held once, structured properly, and read by every
surface that needs it. Four initiatives already on the 2026 backlog are treating the customer facing
symptoms of it separately, which is why several of them keep stalling.

One number is missing and it is the number that makes this fundable: how many hours the Ecommerce
team spend on manual product maintenance, and what those hours cost. David owns producing it. Until
it exists there is a strong customer case here and no business case.

---

## The three problems

| | Problem, as raised | Root cause named |
|---|---|---|
| **A** | The Ecommerce team carry too much manual work maintaining products, updating every attribute by hand. Cost in hours unknown. | Product data has no single source of truth, so maintenance is repeated per surface. |
| **B** | PLPs are not showing the right products. | The data structure does not hold what filters and cards need, and hand entry introduces error on top. |
| **C** | Localisation is not routing correctly. US customers land on UK English pages and see the wrong price and the wrong content. | Locale is not a property of the delivery layer, so market, currency and content come apart. |

**Evidence marking used throughout.** Strong means it is supported across studies or by instrumented
data. Directional means it is supported but not yet tested. Single voice means one participant said
it. Not held means we do not have the figure and should not estimate it.

---

## 1. Customer value

All three land on the same customer moment. Roughly 92% of visitors drop off in the interest and
desire phases, and that is where every symptom below sits. **Strong.**

### A. Manual maintenance

Customers never see the process. They see the output, and the output is where hand entry fails.

Examples already in the research and the data:

- A Glenfinnan Viaduct page with no departure attached received 1,049 sessions. Customers arrived at
  a product they could not buy. **Strong, instrumented.**
- "Excludes accommodation" reads as a flat exclusion on tours where accommodation is in fact
  available to add. One Segment D participant mentally rejected a tour on that basis before the
  moderator corrected it. **Strong.**
- One booker did not know Rabbie's booked the hotels until told in the interview. Accommodation type,
  price range and included attractions currently sit in the booking flow rather than on the tour
  page. **Strong.**
- "Age rating: 5 years plus" was misread by two participants. **Directional.**

Each of those is an attribute maintained by hand. The volume of hand maintained attributes sets the
error rate a customer meets, and nobody currently measures either. Whether every example above is
caused by manual entry rather than by content decisions is an inference, and should be checked with
the Ecommerce team rather than asserted.

**Customer value of fixing it.** Product information a customer can trust. Fewer dead pages. Fewer
tours mentally rejected on a wrong label. The specific gain is in the interest phase, where a
customer is still deciding whether Rabbie's has what they want.

### B. PLPs showing the wrong products

This is the strongest customer evidence of the three.

- Customers report that filters do not work. **Strong, qualitative. Not instrumented.**
- Some returning visitors gave up looking for tours they had booked before. Those are the highest
  intent people on the site. **Strong.**
- A European tour search dead end produced a hard stop rather than a workaround. The participant said
  she would simply stop looking rather than contact Rabbie's. **Single voice, high consequence.**
- 74% of homepage visitors use neither navigation nor search. Of those who do, search converts at
  23.98% and navigation at 18.73%. The two routes into the catalogue both depend on the data
  underneath. **Strong, instrumented.**
- Tour stop data may be absent from the structure entirely. Customers search Google for specific
  places they want to visit. If stops are not in the data, Rabbie's does not appear for those
  searches and cannot show stops on cards. **Directional. The check has not been completed.**
- Customers are doing the structuring work themselves. One compared tour maps by hand. One wrote her
  own checklist to compare stops. One emailed Rabbie's to ask whether two tours fitted together
  because end dates were not shown. **Strong across sessions.**

**Customer value of fixing it.** A customer can find the tour that matches what they want, filter to
it reliably, compare two tours without a spreadsheet, and re-find a tour they have already seen.

### C. Localisation routing

- The site addresses UK customers as first time visitors to Scotland. UK is now 72% of US demand, up
  from 54%. UK customers already know the country, care more about price, book later, and trust
  different signals: ABTA and ATOL rather than the current set. **Strong on the copy mismatch.**
- Currency decides who books, not who travels. One UK participant booked so the transaction stayed in
  Sterling rather than involving Australian dollars for the friends she was visiting. Cross border
  group bookings route to whoever avoids the exchange rate. **Single voice, but it describes a
  mechanism rather than a preference.**
- Acquisition is increasingly first time visitors: 51% to 77% over the period measured. A first time
  visitor served the wrong market's page has no prior knowledge to correct it with. **Strong,
  instrumented.**

**Evidence boundary, and it matters.** No research participant has been observed landing on the wrong
locale. The routing defect is a stated observation from Michelle, corroborated by the copy and trust
signal findings rather than by direct evidence. This should be verified from the data before the
document goes to exec. Tech can establish what share of sessions are served a locale that does not
match their market. That check is cheap and it converts this strand from stated to instrumented.

**Customer value of fixing it.** A customer sees the price in the currency they will pay in, the
trust signals their market recognises, and content written for someone who knows what they already
know.

### What connects the three

Direct Packages, the PLP filter data structure, the Buy Box redesign and the landing page work are
all treating the customer facing side of one underlying problem. Four separate initiatives, four
separate scopes, one cause. That is why fixing them individually keeps producing partial results.

---

## 2. Business value

### A. The hours, and what they are worth

This is the half of the case that does not exist yet. The calculation is simple and the inputs are
not held.

| Input | Value | Owner |
|---|---|---|
| Products maintained | Not held | David, Ecommerce |
| Attributes maintained per product | Not held | David, Ecommerce |
| Update frequency, by season | Not held | David, Ecommerce |
| Ecommerce hours per week on manual product maintenance | **Not held. This is the blocking number.** | David, Ecommerce |
| Fully loaded cost per hour | Not held | Michelle, with finance |
| Rework hours caused by entry error | Not held | David, Ecommerce |
| **Annual cost of manual maintenance** | **Hours per week x 52 x cost per hour** | Output |

Two weeks of time logging would produce a defensible figure. An estimate from memory would not, and
would be the first thing challenged in the room.

**Do not stop at the labour saving.** The hours are also capacity. Ecommerce time spent correcting
attributes is time not spent on merchandising: shifting demand to under filled departures, shoulder
season, and the high traffic low conversion tours. Revenue per session runs roughly £4.50 to £7.60 on
the top tours, against North Coast 500 at £1.81, Isle of Arran day tour at £2.32 and Glenfinnan
Viaduct at £0.75. Closing part of that spread is merchandising work, and it needs the people who are
currently doing data entry.

### B. What the current structure is blocking

Every initiative that touches product data pays a tax:

| Initiative | Backlog position | How it is blocked |
|---|---|---|
| Improve PLP data structure | Initiative 5. **Blocked.** Effort TBC. | Recorded as blocked on July CRO test completion. Michelle's framing points at a broader cause. Reconcile. |
| Personalisation, compare tours | RICE rank 12, 5.5 days | Compare needs the tour stop data check first. |
| Landing page templates | Effort TBC, likely the largest piece in its group | Paid search page plan partly depends on the tour stop check. |
| Navigation redesign | Delivery priority 1, in QA | Depends on URL taxonomy standardisation. |
| Show stops and end dates on cards | Part of PLP and Buy Box work | Blocked on the data structure check. |

Nine initiatives on the tracker carry effort marked TBC, including three of the four largest
workstreams. Scoping is hard partly because the ground they sit on is not established.

### C. Paid media efficiency

Traffic costs more than it did. Google return on ad spend on non brand campaigns fell from 9.8 to 4.3
between January and July 2026. Meta cost per booking rose from £17 to £49 between May and July against
the same months last year. **Strong, instrumented.**

The consequence is arithmetic. A page that cannot show the right product, or shows the wrong market's
price, wastes more money per visit in September than it did in January. The cost of the defect rises
with media inflation whether or not anyone fixes it.

### D. What cannot be claimed here

We cannot forecast a revenue number from what Rabbie's currently holds. Revenue split by product,
margin by line, and load factor on scheduled departures are all not held, and sales are not currently
tagged by product. Any revenue projection in this document would be invented. Saying that plainly is
stronger than modelling it, and it is also an argument for the data fixes.

---

## 3. Outcomes

Written as outcomes, not solutions. The technical team should bring the solution, because they own
the system and they will know options we do not.

| | Outcome | Test of whether it has been met |
|---|---|---|
| **O1** | Product data is held once, in one place, as the source of truth. | An attribute has exactly one place it can be changed. |
| **O2** | An attribute entered once appears everywhere it is relevant, without re-entry. | Adding a departure updates the tour page, the PLP card, the filters and the sitemap with no further action. |
| **O3** | Filters and cards read structured data, not free text. | A filter result can be predicted from the data without a human checking the page. |
| **O4** | Tour stops exist as structured, queryable data. | A place name can be queried and returns every tour that visits it. |
| **O5** | A visitor is served the market, currency and content that match where they are, and can change it deliberately. | Locale is observable in the data and misrouting is measurable rather than anecdotal. |
| **O6** | Ecommerce time moves from maintenance to merchandising. | Hours logged against maintenance fall, and hours against merchandising rise. |

**Constraints any solution has to meet.** It cannot stall the navigation redesign, currently in QA,
or Direct Packages 2.0, currently in build. Any change to URL structure or taxonomy needs Salience
sign off before it ships, because place name and destination search visibility depends on it. Michelle
has already asked Jack at Salience whether the current structure carries an SEO cost, and that answer
should land in this document before it goes further.

**What this document is not asking for.** It does not name a technology, a platform, or a rebuild.
Asking for the outcome keeps the decision with the people who own the system.

---

## 4. Business impact

### Where the money is

Three routes, in the order the evidence supports them.

1. **Wasted paid spend on pages that cannot convert.** Best evidenced. Media cost is rising, first
   time visitor share is rising, and the landing surfaces for that spend are the PLPs and tour pages
   affected by all three problems.
2. **Unsold seats on departures already running.** If costs are largely fixed per departure, which is
   the standard shape for scheduled small group operators but is not yet confirmed by Rabbie's, then
   incremental passengers on running tours are close to pure margin. The high traffic low conversion
   tours would then be unsold seats rather than wasted traffic. **This turns on the load factor
   question, which is not held.**
3. **Ecommerce labour.** Directly recoverable once the hours are known, and the easiest of the three
   to defend in a budget conversation.

### Where the risk is

- **Price display to customers in another market.** Showing a price in the wrong currency, or a price
  that is not the total a customer will pay, carries consumer protection exposure in the UK and in
  the US markets Rabbie's sells into. **Flagged, not advised. The current regulatory position needs
  verifying before this line goes in front of exec.** Treat it as a reason to check, not as a
  finding.
- **Trust marks shown to the wrong audience.** ABTA and ATOL are claims about protection, and which
  protections apply can depend on where the customer is and what they have bought. Serving those
  badges by template rather than by locale should be checked with whoever owns the compliance
  position.
- **Search visibility.** Any restructure touches URLs and taxonomy. That is upside if stops enter the
  data and downside if it is done without Salience. Jack's answer is outstanding.
- **Compounding delivery cost.** Templates for homepage, PLP, PDP, landing page and late availability
  are all in scope across current initiatives with no shared component definition, and components are
  being built per initiative outside the library. Every template built on the current structure raises
  the cost of changing it later. This is a governance problem as much as a technical one.

### Where the risk of not acting is

Localisation routing is not on the 2026 initiatives backlog at all. It affects the price and content
shown to a significant share of customers, which makes it a revenue issue as well as a user
experience one. It needs either a tracker entry or an explicit decision not to add one. Michelle owns
that call.

---

## 5. Success metrics

### Instrument first. Four of these baselines do not exist.

| What to instrument | Why it blocks | Owner | Cost |
|---|---|---|---|
| PLP filter usage: which filters are used, which return nothing, how often | The entire filter position currently rests on qualitative reports with no instrumentation. It is the cheapest item on the backlog. | Liberandum, Sarita | Low |
| Product tags on sales | Without it, no result can be read by product line, and day tours are roughly 80 in 100 sales, so every mixed cohort reads as day tours. | Rabbie's, with Evolution | One of four data fixes already requested |
| Ecommerce maintenance hours | No baseline, no saving to claim. | David | Two weeks of logging |
| Locale routing accuracy: share of sessions served a locale matching their market | Converts strand C from stated to measured. | Tech | Low |

Do not design filter changes before the filter usage data exists.

### Leading indicators, readable within weeks

| Metric | Strand | Baseline |
|---|---|---|
| Filter searches returning zero results, as a share of filter uses | B | Not held |
| Tour pages live with no departure attached | A | At least one known: Glenfinnan Viaduct, 1,049 sessions |
| Sessions served the wrong locale, as a share of total | C | Not held |
| Ecommerce hours logged against manual maintenance, per week | A | Not held |
| Attribute corrections and rework raised per month | A | Not held |
| Search and navigation entry rates into the catalogue, against the 74% who use neither | B | 74% use neither. Search converts 23.98%, nav 18.73% |

### Lagging indicators, the outcome measures

| Metric | Strand | Baseline | Caveat |
|---|---|---|---|
| Revenue per session on the low performing high traffic tours | A, B | £0.75 to £2.32 on the three named | Merchandising and data both move this. Do not attribute it to one. |
| PLP to tour page progression | B | Not held | Needs the filter instrumentation first. |
| Tour page to basket, split by product | A, B, C | Multi day 13 in 100. Day tours 14 in 100. Edinburgh only, no date range. **Re-pull before quoting externally.** | Product split currently inferred from pages viewed, not from what was bought. |
| Conversion by market, US and UK separately | C | Not held at this cut | The point of strand C is that a single blended figure hides it. |
| Place name organic visibility for tour stops | B | Not held | Salience owns the measure. |
| Ecommerce hours redirected to merchandising | A | Not held | The saving is only real if the time goes somewhere useful. |

### Two measurement cautions to keep on the page

**GA4 is accurate but booking anchored.** It reports the final act of booking, not the consideration
window. That is a targeting bias, not a measurement error. The Safari seven day cookie cap and cross
device identity loss compound it.

**Attribution windows must differ by product.** About 69.3% of bookings happen within 10 days of the
visit, so a four week read captures most day tour decisions and only a fraction of multi day ones. A
multi day result read on a four week window will understate the effect.

---

## Inputs needed to complete this document

| Question | Owner | Blocks |
|---|---|---|
| Hours per week on manual product maintenance, and what drives them | David, Ecommerce | The entire business value section |
| Fully loaded Ecommerce cost per hour | Michelle, with finance | The annual cost figure |
| Number of products and attributes maintained by hand | David, Ecommerce | Sizing the problem |
| Does the current structure carry an SEO cost | Jack, Salience | Outstanding. Michelle has asked. |
| Share of sessions served the wrong locale | Tech | Moves strand C from stated to measured |
| Has the tour stop data check been completed | Tech | Strand B, and the compare feature |
| Reconciling initiative 5's recorded blocker with this framing | Michelle, with Tech | The tracker currently says blocked on July CRO test completion |
| Does localisation routing get a tracker entry | Michelle | It is currently on no list |
| Current regulatory position on price and currency display in both markets | To be assigned | The risk line in section 4 |

---

## Version note

v1, 09/09/2026. First draft, written from the 09/09/2026 conversation with Michelle. Sources: the
2026 UX initiatives tracker, the rolling research synthesis across four waves, GA4 exports held in
the project, and the August time in market analysis. Figures marked "not held" are absent from the
project, not omitted from this draft. Nothing here has been agreed with Rabbie's.
