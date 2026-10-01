# Workshop opportunities, mapped to the initiative backlog

**Date:** 24/09/2026
**Author:** Joe Collingwood, Sunny Lemons
**Status:** Draft v2, for discussion with Michelle and Alex. Not agreed.
**Sources:** All agency workshop post-it wall, September 2026 (`+RB_ All_agency_workshop_sep 2026_post_it_notes.md`); State of the Nation deck (`sep2026_state-of-the-nation_rabbies_performance.md`); initiatives tracker synced 05/09/2026 (`initiatives.md`); product data architecture case v2; booker and private tours research.
**Boundary:** Votes show what the room cared about, not what the customer data ranks. Where the two disagree, the data should win. Effort thresholds used to classify items are Sunny Lemons proposals, not developer estimates.

**Version note.** Supersedes v1 of the same date. What changed and why:

- Every one of the 68 post-its is now assigned to exactly one opportunity, and listed under it. v1 left several unassigned.
- Each item is classified by type (below) and labelled by team: UX, SEO, Paid media, Social & Content, Tech, Ops.
- Product data is now the foundation opportunity, OP-01, with the other opportunities' dependencies on it counted. This reflects the position already agreed outside the workshop.
- Removed v1's "roughly 1.9 FTE" figure. Ecommerce team size is not held anywhere in the project, so the figure had no source.
- Corrected the guide claim. "Roughly 90% of experience quality" comes from one day-tour customer, after the tour. v1 presented it as customers in general.
- Removed v1's claim that most of the 92% drop-off sits on listing pages. The 92% covers the whole interest and desire phase, and nothing held splits it by page type.
- Added compliance flags on scarcity and sale price messaging, and on the consent basis for post-booking email.

---

## The answer, up front

The wall reduces to eleven customer opportunities plus one on how the agencies work together. About a third of the room's votes (110 of 314) sit on problems that the product data rebuild fixes in whole or in part. That makes the rebuild the most important thing on the list even though it drew only 18 direct votes. It should be a new parent initiative. Tracker initiative 5, Improve PLP data structure, becomes its first consumer.

The biggest single cluster is accommodation, at 49 votes. It is also where multi-day, the 2027 priority, loses people. Its cheapest fix is an operations decision to cut the number of accommodation scenarios, and that should happen before Direct Packages builds a selector around them.

Most items are already covered by an initiative on the tracker. Two genuinely new initiatives are needed: the product data foundation and a multi-tour basket. Nine items are decisions rather than builds, and none of them has a named owner yet.

---

## How items are classified

Each item gets exactly one type.

| Type | Meaning | What happens on the tracker |
|---|---|---|
| **Covered** | An existing initiative already scopes this | Add the workshop evidence to that row. No new row |
| **Extend** | An existing initiative is the right home, but this is outside its current scope | Change note on that row, new sub-task |
| **Task** | One team, no new capability, a few days, no dependencies | Done inside business as usual. No tracker row |
| **Small project** | Bounded, one deliverable, up to roughly three weeks or more than one team | Tracker row, no RICE parent needed |
| **New initiative** | New capability or platform change, several teams | New parent row, RICE scored |
| **Decision** | No build. A commercial, operational or governance choice | Needs a named owner and a date, not a ticket |

**When:** Now means this quarter with no unresolved dependency. Next means it waits on something named.

**Scope note.** Tech, SEO and Paid media items belong to Rabbie's teams, Salience or Liberandum. Sunny Lemons' contract excludes software development, copywriting and campaign execution. Where an item is labelled Tech, our part is requirements, UX and QA.

---

## Summary

| Ref | Opportunity | Votes | Labels | 2027 focus it serves |
|---|---|---|---|---|
| OP-01 | Product data held once, read everywhere | 18 direct, 110 dependent | Tech, Ops, SEO | All four. The enabler |
| OP-02 | Finding a tour that fits | 28 | UX, Social & Content, Tech, Ops | Scaling Scotland, non-Scotland |
| OP-03 | Knowing where you will sleep | 49 | UX, Social & Content, Ops, Tech | Multi-day |
| OP-04 | Showing what the tour is, and why us | 29 | Social & Content, UX, Paid media | Target markets, multi-day |
| OP-05 | Deciding and paying with confidence | 31 | UX, Tech | Target markets, multi-day |
| OP-06 | Booking more than one tour | 34 | UX, Tech, Ops | Scaling Scotland |
| OP-07 | Keeping what I found | 25 | UX, Tech | Multi-day |
| OP-08 | The gap between booking and travelling | 40 | Social & Content, UX, Tech, Ops | Multi-day |
| OP-09 | Capturing intent we currently lose | 30 | Social & Content, Paid media, UX, Tech, Ops | Target markets |
| OP-10 | Speaking to each market properly | 26 | SEO, Paid media, Social & Content, UX | Target markets, non-Scotland |
| OP-11 | Private tour intent on the scheduled catalogue | 1 | Ops, UX | None directly. Commercially weighted |
| OP-12 | How the agencies work together | 3 | Ops | All four |

Vote totals sum each post-it once. Where two groups raised the same problem, both notes are counted, so a cluster's total can be higher than any single note.

---

## The framing point to make first

Michelle's note asked us to reduce spend on new customers and focus on retention. The customer data does not support next-year retention as the main lever:

- About half of "repeat" bookings are the same holiday, booked within 14 days of the first tour ending.
- 37 to 41% of second bookings happen on the same day as the first.
- UK repeat is 16.4%, the lowest of all markets, against 24.0% Canada, 23.1% Australia and 21.0% US.
- Email permission on new bookers is 8.05% in 2026, so most recent customers cannot be emailed.

The retention opportunity sits almost entirely **inside the current trip**: the second tour, the gap before travel, the day before. That is OP-06 and OP-08, and it costs no acquisition spend. Retention in the strict sense, bringing people back next year, is blocked until the permission rate is explained (OP-09.1).

---

## OP-01 · Product data held once, read everywhere
**18 direct votes. 110 votes across 24 post-its depend on it in whole or part.**

**From the wall.** CMS backend limits the ecommerce team (3). Tour page and CMS build too manual and complex (5). 65% of ecommerce team time spent updating products, although the data already sits in Traverse (8). Ecommerce bandwidth (2).

**Already established, not on the wall.** The product data structure has to be rebuilt. There are two reasons. First, so filters work and listing pages can serve every product properly. Second, for efficiency: the ecommerce team spend 50 to 60% of their time each month updating products by hand, re-keying data that already exists in Traverse into the CMS. That leaves room for human error and wrong product attribution.

**Evidence.** The September 2026 audit found 79 of 120 trade sheet products, 66%, with no listing page link a search engine can follow, 64 of 120 missing their taxonomy breadcrumb, and at least 48 links across 23 content entries sending visitors to the wrong market. Every product runs in three locales (en-gb, en-us, en-eu). Whether each is maintained once or three times is not known.

**The time figure needs one number, not two.** The wall says 65% and the working estimate is 50 to 60%. Both are estimates, and neither comes from a time log. The range is 50 to 65% until measured. Measuring it is OP-01.1, and it is the figure that makes the rebuild fundable.

**Why a new initiative rather than extending initiative 5.** Initiative 5 is scoped as a listing page data fix, owned by Tech, and recorded as blocked on the July CRO test. The rebuild serves listing pages, tour pages, the buy box, landing pages, SEO and the ecommerce team's month. Filed as a listing page sub-task, it is understated and cannot be funded as what it is. Initiative 5 folds into it as the first surface it serves.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-01.1 | Two-week time log splitting first-pass entry from rework, per locale | Task | Ops | Now |
| OP-01.2 | Establish whether each product is maintained once or once per locale | Task | Ops, Tech | Now |
| OP-01.3 | Define the attributes every surface needs: duration, destination and region, tour type, stops, accommodation, departure hub, market pricing, availability | Small project | UX, Tech, SEO, Ops | Now |
| OP-01.4 | Traverse to CMS pipeline, so product data is entered once | New initiative | Tech | Next, after OP-01.3 |
| OP-01.5 | Re-scope initiative 5 into OP-01 and remove its block on the July CRO test | Decision | Tech, Ops | Now |

**Measure.** Ecommerce hours per month on product data. Audit defect counts re-run quarterly against the September baseline.

**Boundary.** The engineering solution is Rabbie's to choose. The architecture case deliberately does not specify one. OP-01.3 is where Sunny Lemons contributes: what each customer-facing surface needs from the data.

### What depends on OP-01

| Opportunity | Items that need the rebuilt data |
|---|---|
| OP-02 | Filters, tour card content, listing order by region, templates by tour type |
| OP-03 | Accommodation shown on cards and listing pages. The tour page version can be entered by hand in the meantime |
| OP-04 | Stops, points of interest and a whole-trip map |
| OP-05 | Availability, seats left and sale price, all of which live in Traverse |
| OP-07 | Compare, which needs like-for-like attributes |
| OP-10 | Locale leaks, which are hand-entered prefixes. Need-based landing pages built from attributes |

---

## OP-02 · Finding a tour that fits
**28 votes**

**From the wall.** Decision fatigue on listing pages (6). Tour card design (5). Too much choice, customers may need help planning (1). Filtering and finding suitable tours (2). Hard to find a tour that fits the existing filters (6). One tour page template for every tour type (1). Page layouts and flexibility (3). Listing pages assume destination knowledge (2). Scotland tours dominate listing pages (2). Low-ranking tours on listing pages less likely to convert (0).

**Evidence.** 74% of homepage visitors use neither the navigation nor search. Customers say the filters do not work, and some returning visitors gave up looking for tours they had booked before.

**2027.** This is where scaling Scotland and growing non-Scotland collide. If Scotland fills listing pages by default, non-Scotland products cannot grow whatever is spent on them. Listing order is a commercial choice and should be made deliberately.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-02.1 | Merchandising rules for listing order, including where non-Scotland and low-ranking tours sit | Decision | Ops, Social & Content | Now |
| OP-02.2 | Tour card content and copy that does not assume destination knowledge, within current data | Small project | UX, Social & Content | Now |
| OP-02.3 | Filters rebuilt on the new attributes | Covered by initiative 5, now inside OP-01 | Tech, UX | Next |
| OP-02.4 | Tour page templates by tour type (day, multi-day, private) and layout flexibility | Extend initiative 1, IA restructure, with 17, design system | UX, Tech | Next |

**Measure.** Listing to tour page progression. Filter use leading to a tour view.

---

## OP-03 · Knowing where you will sleep
**49 votes, the largest cluster**

**From the wall.** Accommodation range options (4). Price uncertainty, Direct Packages not everywhere (2). Complicated accommodation scenarios for customers and operations (10). Accommodation not visible until the booking flow (11). Accommodation information on tour pages (8). Accommodation information earlier than the tour page (5). Accommodation too complex, simplify (9).

**Evidence.** 60% drop-off at the accommodation step in the multi-day booking flow. Three participants entered checkout just to find accommodation information. Multi-day is -20% to budget and the weakest 2027 forward gain at +32.2%.

**Sequence matters here.** Cut the scenarios first, then show them, then build the selector. Building Direct Packages' selector around scenarios that are about to be cut is wasted build.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-03.1 | Operations decision to reduce the number of accommodation scenarios | Decision | Ops | Now |
| OP-03.2 | Accommodation type, price range and inclusions on multi-day tour pages | Covered by initiative 2, sub-task "Surface accommodation details on tour page" | Social & Content, UX | Now |
| OP-03.3 | Accommodation shown earlier, on cards and landing pages | Extend initiative 2, same sub-task | Social & Content, UX | Next, needs OP-01 |
| OP-03.4 | Direct Packages rollout and price certainty | Covered by initiative 2, Direct packages 2.0 | Tech | Next, after OP-03.1 |

**Measure.** Drop-off at the accommodation step. Multi-day checkout to purchase, currently 13 in 100 on the Edinburgh export.

---

## OP-04 · Showing what the tour is, and why us
**29 votes**

**From the wall.** Product differentiation (5). Driver-guides not visible on the site (10). Not enough driver-guide content (1). USPs explaining the brand to new visitors (6). Static landscape ad content can read as a walking tour (1). Little detail on destinations, points of interest and attractions (4). One overall map for multi-day rather than a per-day itinerary (2).

**Evidence.** Rabbie's has two genuine differentiators: driver-guides, and depth of service on logistics and accommodation. Small groups and not having to drive are category parity and should not lead. Guide evidence is strong on rebooking and all post-tour. The link from guide visibility to conversion is untested (`assumptions.md` A6, medium). One day-tour customer put roughly 90% of experience quality down to the guide. That is a single voice.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-04.1 | Guide profiles on tour pages | Covered by initiative 2, sub-task "Introduce guide module on PDP" | Social & Content, UX | Now, needs a named operations contact for guide content |
| OP-04.2 | First-visit USP block built on the two real differentiators | Task | Social & Content | Now |
| OP-04.3 | Ad creative that shows a guided vehicle tour, not a walking tour | Task | Paid media, Social & Content | Now |
| OP-04.4 | Destination and attraction detail, and a whole-trip map for multi-day | Small project | Social & Content, UX, Tech | Next, needs OP-01 stop data |

**Measure.** Tour page to availability check, with the guide module against without.

---

## OP-05 · Deciding and paying with confidence
**31 votes**

**From the wall.** No availability information on tour pages (7). Fewer steps and no doubts in the booking flow (6). Split payment options not visible (5). No sale price in the buy box (4). No seats-left indicator (4). Currency only GBP and USD despite Canadian and Australian markets (5).

**Evidence.** Canada has the highest ABV at £310 and Australia £271, and both are asked to pay in a foreign currency. Multi-day converts 13 in 100 from basket to payment against 38 in 100 for day tours.

**Compliance flag.** Seats-left counts and was/now pricing are both regulated claims in UK consumer law. Scarcity must reflect real inventory, and a reference price must be genuine. Check the current CMA position before either ships. Flagged, not advised on.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-05.1 | Availability and seats left on the tour page and buy box | Extend initiative 3, Buy Box redesign | UX, Tech | Next, needs the Traverse feed through OP-01 |
| OP-05.2 | Sale price shown before and after in the buy box | Extend initiative 3 | Tech, UX | Next |
| OP-05.3 | Split payment visibility | Covered by initiative 9, Deposits, and the deposit messaging in initiative 3 | UX, Social & Content | Next, with deposits |
| OP-05.4 | CAD and AUD currency | Small project | Tech | Now to scope. Display and charge currency are different builds |
| OP-05.5 | Fewer steps and fewer doubts in the booking flow | Covered by initiative 2, sub-task "Booking flow optimisations" | UX | Next |

**Measure.** Step completion through the flow. Multi-day checkout to purchase.

---

## OP-06 · Booking more than one tour
**34 votes**

**From the wall.** No basket, one tour per booking because of finance restrictions (16). Cannot book several tours at once, same cause (8). Shortlist several holidays to book together (7). Attraction bundle upsell (3).

**Evidence.** Customers already buy a second tour. We just make them do it twice. 37 to 41% of second bookings are made the same day as the first. Loch Ness, Glencoe and the Highlands is the top second tour after three of the best sellers, at 29 to 31%. More seats sold on departures already running is exactly the 2026 focus: more volume from inventory already secured.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-06.1 | Cross-sell on the confirmation page and email, using the known first-to-second tour pairs | Extend initiative 13, related tours, to the post-booking moment | UX, Social & Content | Now |
| OP-06.2 | Establish the finance restriction and whether any workaround exists short of a basket | Decision | Ops, Tech | Now |
| OP-06.3 | Multi-tour basket | New initiative | Tech, UX | Next, after OP-06.2 |
| OP-06.4 | Attraction bundles | Small project | Ops, Tech | Next, after OP-06.3 |

**Measure.** Share of bookings with more than one tour. Second bookings taken in the same session.

---

## OP-07 · Keeping what I found
**25 votes**

**From the wall.** No shortlist (5). No compare (7). Cannot build "My Trip" linking dates and itinerary (1). The site does not remember preferences or dates (8). No aggregated data to serve by propensity (4).

**Evidence.** 52% of multi-day buyers view two or more tours before purchase. Customers compare using spreadsheets, browser tabs and emailed lists of links.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-07.1 | Persist passengers and dates across the session | Covered by initiative 4 | Tech | Now |
| OP-07.2 | Recently viewed | Covered by initiative 13 | Tech | Now |
| OP-07.3 | Shortlist and compare, with "My Trip" as a later extension of the shortlist | Covered, split between initiative 10 (shortlisting) and 13 (compare). Consolidate into one | UX, Tech | Next, compare needs OP-01 |
| OP-07.4 | What customer data should drive propensity, and who owns it | Decision | Tech, Ops | Next, after OP-09.1 |

**Measure.** Tours viewed per session. Return rate to a saved list.

---

## OP-08 · The gap between booking and travelling
**40 votes**

**From the wall.** Not clear what happens next after booking (6). No warm-up or excitement before the tour (10). No SMS for critical information or the day-before pickup, time and guide name (10). No customer portal, and the old manage-booking page needs removing because of security issues (10). No post-purchase flow for long lead-time bookers (4). Email links to a generic tour page rather than the itinerary (0).

**Evidence.** Lead time from booking to travel runs from about 28 days to over 150 depending on departure hub, and averages 85 days from Australia. Multi-day books earlier than day tours. That is months of silence in which we neither reassure nor sell.

**Security flag.** The old manage-booking page is a known security risk. Its replacement currently sits in initiative 10, which depends on Deposits completing. Retiring the risk should not wait for a new portal. Split the two.

**Consent flag.** Booking information messages do not need marketing consent. Upsell content inside them may. Check the PECR position before the post-booking sequence carries offers.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-08.1 | "What happens next" on the confirmation page and email | Task | UX, Social & Content | Now |
| OP-08.2 | Point booking emails at the booked itinerary, not the generic tour page | Task | Tech | Now |
| OP-08.3 | Post-booking email sequence by lead time, multi-day first | Small project | Social & Content | Now |
| OP-08.4 | Day-before SMS with pickup point, time and driver-guide name | Small project | Tech, Ops | Now |
| OP-08.5 | Remove or secure the old manage-booking page | Task | Tech | Now, urgent |
| OP-08.6 | Customer portal | Covered by initiative 10, sub-task "Auth, shortlisting, deposits and booking management" | Tech, UX | Next |

**Measure.** Inbound contacts asking whether a booking is confirmed. Pre-tour add-on and second-tour bookings made from the sequence.

---

## OP-09 · Capturing intent we currently lose
**30 votes**

**From the wall.** Reduce spend on new customers and focus on retention (Michelle, not voted). No lead generation (3). Rebook offer is one generic code for everyone (6). No save for later or other lead capture in the booking funnel (3). No abandoned basket lead capture and retargeting (4). No recommend a friend (7). Retargeting across Meta, email and web limited to none (4). Marketing content and CRM journeys not joined up (3).

**A contradiction to resolve first.** The State of the Nation deck lists "Built and enhanced abandoned basket" as delivered this year. The wall says it does not exist. Establish what is live before scoping anything here.

**Blocker.** Email permission on new bookers is 8.05% in 2026, against 96 to 99% on every cohort to 2020. Nobody knows whether this is a tracking change or a real collapse in consent. Everything in this cluster that routes through email waits on the answer.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-09.1 | Establish the cause of the 8.05% permission rate | Task | Ops, Tech | Now, gates the cluster |
| OP-09.2 | Audit what abandoned basket and retargeting actually exist, then close the gaps | Task, then extend whatever exists | Paid media, Social & Content | Now |
| OP-09.3 | Referral prompt at confirmation | Covered by initiative 10, sub-task "Referral mechanism". Decouple from the account build | UX, Social & Content | Now |
| OP-09.4 | Segment the rebook offer | Task | Social & Content | Now, after OP-09.1 |
| OP-09.5 | Save for later and lead capture in the funnel | Small project | UX, Tech | Next, with OP-07.3 |
| OP-09.6 | Single owner for how marketing content and CRM journeys join up | Decision | Ops | Now |

**Paid media caveat.** Paid revenue was misattributed to Direct and Organic from 11/05/2026 to 22/09/2026. Any retargeting baseline from that period needs re-pulling.

**Measure.** Recovered baskets. Referred sessions, then referred bookings.

---

## OP-10 · Speaking to each market properly
**26 votes**

**From the wall.** No market or need-specific landing pages (6). Low brand awareness outside Scotland (1). US SEO (5). Cross-geo signals confusing Google (5). No Canada and Australia focus (4). Not knowing what customers want to target (1). Paid feedback signals dominated by Scotland day tours (3). No paid strategy split between single and multi-day (1).

**Evidence.** The US produces 42.6% of direct bookings at 1.86% conversion. The UK produces 16.2% at 0.78%. Canada and Australia carry the highest ABVs. The audit found at least 48 links sending visitors to the wrong market, all hand-entered. The private tours research found Rabbie's is filed as a Scotland-only company. One participant gave a week of European business to another operator for that reason.

**Changed since the tracker was last scored.** Initiative 14, local content, is RICE rank 2 on the basis that UK growth is the better bet. That belief is now low confidence (`assumptions.md` A19), and management's own line is that quality, not volume, is the lever. The work still stands, but it should be framed market by market, not UK first.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-10.1 | Market-specific copy on the highest-traffic pages | Covered by initiative 14. Reframe from UK first to market by market | Social & Content, SEO | Now |
| OP-10.2 | Remove hand-entered locale prefixes from content | Task. Root fix sits in OP-01 | SEO, Social & Content | Now |
| OP-10.3 | Market and need-based landing page templates | Covered by initiative 8, sub-task "Overall templates" | UX, Social & Content, SEO | Next |
| OP-10.4 | US, Canada and Australia search programme | Small project, Salience's to lead | SEO | Next |
| OP-10.5 | Paid strategy split by product and market, with conversions tagged by product so bidding is not steered by Scotland day tours | Small project | Paid media, Tech | Now. Check whether the new datalayer already carries product tags |
| OP-10.6 | How much 2027 effort non-Scotland gets, and against what measure | Decision | Ops, Paid media, SEO | Now |

**Measure.** Conversion by market. Landing page to tour page progression by campaign type.

---

## OP-11 · Private tour intent on the scheduled catalogue
**1 vote, but commercially weighted**

**From the wall.** People who want a private tour also go through scheduled tours. Investigate or test why (1).

**Partly answered already.** In the private tours research, one organiser used scheduled tour pages to learn the destinations and as a price anchor, running a scheduled tour through the passenger selector just to see what her group would cost. Private tours are -28% to budget, +24% year on year, and the 2027 forward book is up 116.5%.

**Gate.** Nothing that grows private volume should be funded until private margin has been compared with filled seats on scheduled departures (`assumptions.md` A20). That comparison does not exist.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-11.1 | Qualification at first contact: party size, age spread, a named constraint | Covered by the private tours service model memo, which needs no website change | Ops | Now |
| OP-11.2 | Private tour route from scheduled tour pages for large parties | Task | UX, Social & Content | Next, after the margin comparison |

---

## OP-12 · How the agencies work together
**3 votes**

**From the wall.** Not always clear what outcome we expect from a piece of work (2). CRO seems to break SEO and vice versa (1).

Neither is a ticket. Both are rules.

| Ref | Item | Type | Labels | When |
|---|---|---|---|---|
| OP-12.1 | Every opportunity gets one measure and a baseline before it is scoped. The measures above are proposed by Sunny Lemons, not agreed | Decision | Ops | Now |
| OP-12.2 | A sequencing rule between CRO and SEO changes, with a named owner across Liberandum and Salience | Decision | Ops | Now |

---

## What this does to the tracker

**New initiatives, two.**

| Item | Why it is a new parent |
|---|---|
| OP-01.4 Product data foundation, absorbing initiative 5 | Serves every surface and the ecommerce team. Filed as a listing page sub-task it cannot be funded as what it is |
| OP-06.3 Multi-tour basket | New capability, blocked on a finance decision rather than on design |

**Extensions to existing initiatives, five.** Initiative 1 (templates by tour type), 2 (accommodation earlier in the journey), 3 (availability, seats left, sale price), 13 (post-booking cross-sell), and the consolidation of shortlist and compare across 10 and 13.

**Small projects, eight.** OP-01.3, 02.2, 04.4, 05.4, 06.4, 08.3, 08.4, 09.5, plus two led by other agencies, OP-10.4 and 10.5.

**Decisions without an owner, nine.** OP-01.5, 02.1, 03.1, 06.2, 07.4, 09.6, 10.6, 12.1, 12.2. Three of them unblock the most: accommodation scenarios (03.1), the finance restriction on multi-tour booking (06.2), and listing order (02.1).

**Decoupling needed.** Referral (OP-09.3) and the manage-booking security fix (OP-08.5) both sit inside initiative 10, which waits on Deposits. Neither needs to.

---

## How the 2027 focus is served

| Focus | Served by | Honest read |
|---|---|---|
| Scaling Scotland | OP-02, OP-06, and the capacity OP-01 frees for merchandising | Well served, if "scaling" means more seats sold on running departures. Not defined by any metric yet |
| Growing multi-day | OP-03, OP-05, OP-07, OP-08 | Best served. Accommodation is the single biggest lever |
| Understanding target markets | OP-05.4, OP-09, OP-10 | Served on execution. The analysis that says which markets to back, UK volume or Canadian and Australian value, is still not done |
| Non-Scotland growth | OP-02.1, OP-10.2, OP-10.6 | Thin. Almost nothing on the wall is about non-Scotland product, and it has no measure. Without OP-10.6 it will get whatever is left |

---

## Not raised in the room

Three of the strongest items on the existing tracker drew no post-its: mobile tour page layout (RICE rank 1), end dates on the calendar (rank 3) and owned reviews (rank 4, confidence 0.95, the highest on the list). Their absence from the wall is not a reason to deprioritise them. The workshop captured what the room felt, not the whole backlog.

---

## Cheap and fast, this quarter

1. **OP-03.1** Decide to cut the accommodation scenarios. No build.
2. **OP-06.1** Cross-sell on confirmation, using the known tour pairs.
3. **OP-08.1, 08.2, 08.5** Tell people what happens next, fix the email link, and retire the insecure manage-booking page.
4. **OP-04.1 and 04.2** Guide profiles and a first-visit USP block.
5. **OP-01.1** The two-week time log. It costs nothing and it is the number the biggest initiative on this list is waiting for.

---

## Open questions

- Is there a workaround to the finance restriction on booking several tours at once, short of a full basket? OP-06 is blocked on this.
- What is behind the 8.05% email permission rate? It gates OP-09 and the upsell half of OP-08.
- What abandoned basket capability actually went live this year?
- Who in operations owns guide content and the accommodation scenario decision?
- Which of the ecommerce time figures, 50 to 60% or 65%, is closer? Only the time log settles it.
