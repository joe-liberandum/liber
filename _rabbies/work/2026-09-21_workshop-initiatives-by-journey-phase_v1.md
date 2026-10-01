# Initiatives by journey phase: workshop input

**Draft, v1, 21/09/2026.** For the all-agency session, 23 September 2026, Edinburgh. Not delivered.
Source is `initiatives.md`, last synced from `Rabbies_2026_UX-initiatives_Tracking.xlsx` on
05/09/2026. Where this file and the workbook disagree, the workbook wins.

---

## The answer first

**Every one of the 17 initiatives on the UX backlog sits in two of the eight journey phases.** The
tracker's own phase column carries only two values, Interest and Desire. Four phases have nothing on
the backlog at all: pre-awareness, awareness, pre-tour, and tour. Book and advocacy have a handful of
items each, all of them sub-tasks of larger parents rather than initiatives in their own right.

That is defensible, because Interest and Desire is where roughly 92% of drop-off sits and the
engagement is a UX and CRO engagement. It is also the single most useful thing to put on the wall on
the 23rd, because the four empty phases are exactly the ones the other three agencies own. The
backlog describes the website, and the journey is wider than the website.

**Three things are missing before this list can be read as a plan.**

1. **No initiative on the tracker carries a measure of success.** The workbook has a `CRO test` and
   `CRO test focus` column and no success measure column. Every measure in the tables below is
   proposed by Sunny Lemons and has not been agreed by anyone. Baselines are real and sourced.
   Targets are deliberately left blank, because setting them is a job for the room.
2. **Nine of the 17 have an effort of TBC**, including three of the four largest likely workstreams.
   Any sequencing argument is provisional until those are scoped.
3. **Nine carry a named evidence gap**, five of them below 0.6 confidence. The standing rule is that
   a confidence below 0.6 with an effort of TBC is not ready to be scoped, let alone built.

---

## How to read the phase column

Phases here are assigned by function, meaning the job the initiative does for the customer. Where
that disagrees with the tracker's own two-value column, the tracker's tag is shown in the last
column so the divergence is visible rather than quietly corrected. The largest disagreement is
navigation, tagged Desire in the tracker and functionally an Interest-phase initiative.

`Track` records which of the two product journeys the initiative serves, since part one of the day
runs in two tracks. `Both, day skew` means it applies to both but the evidence behind it comes from
day tour behaviour.

---

## Pre-awareness

Someone has a trip in mind and does not yet know that a guided tour is an option.

**Nothing on the UX backlog.** No initiative, no sub-task, no research row.

What Sunny Lemons holds for this phase is an argument rather than an initiative:
`strategy/2026-09_late-booking-is-a-targeting-artefact.md`. Late booking patterns follow late
targeting spend, Australia shows an earlier pattern and functions as the natural experiment, and
booker interviews report consideration windows of months while GA4 records every one of them as a
first-session booking. Confidence in the mechanism is high. Confidence in the size of the recoverable
early window is not.

**Owner on the day.** Paid media and digital PR. This is the phase where Salience and the media side
should be doing the talking, and where Sunny Lemons contributes the evidence that the window exists.

**Proposed measure.** Share of bookings originating from a first session more than 60 days before
departure, tracked by market, against the Australian pattern as the reference. Baseline needs pulling
and is not in `analysis/` today.

---

## Awareness

First contact with the Rabbie's brand.

**Nothing on the UX backlog.**

The finding that matters: discovery is almost entirely third party. Reddit, TripAdvisor, Rick Steves,
Viator, GetYourGuide and personal recommendation. Cold acquisition from search alone is rare, and the
largest spend is aimed at the rarest way in. Three of the four personas make their brand decision
before they reach the site.

A second finding sits here and has no owner: credibility badges are not self-explanatory. B Corp
confused three participants, ABTOT confused one. This matters more as AI overviews surface badges
without the context around them.

**Owner on the day.** Salience, digital PR, social. Sunny Lemons has no initiative to report.

**Proposed measure.** Assisted and third-party referral share of new-visitor sessions, plus
brand-search volume by market. Neither is currently reported to this engagement.

---

## Interest

On site, working out whether there is something here for me.

| # | Initiative | Focus | Status | Track | Proposed measure of success | Tracker phase |
|---|---|---|---|---|---|---|
| 1 | Navigation redesign, customer mental model | Restructure primary nav around departure city, destination, duration, interests, most popular | **In QA** | Both | Reduce the 74% of homepage visitors who use neither nav nor search. Close the gap between search conversion at 23.98% and nav at 18.73% | Desire |
| 1a | Information architecture restructure | Site map, URL structure, page templates. Largest single design workstream | **In Build** | Both | Not suitable for a CRO test. Validate on SEO and internal search metrics | Desire |
| 5 | Improve PLP data structure | Frontend lacks the tour data needed for reliable filtering and tour cards | **Blocked** on July CRO test completion | Both | Filter-use to tour-view rate. Zero-result searches as a share of all searches | Interest |
| 8 | Landing page optimisations | Repeatable story structure so campaigns are not built from scratch | **In Design** | Both | Landing page to PDP progression rate. Named as a major factor in the 92% interest and desire drop-off | Interest |
| 8a | Overall templates | Effort TBC, RICE pending. Likely the largest item in this group | **In Design** | Both | As above, split by campaign type | Interest |
| 8b | Improving late availability functionality | Page has never been reviewed for how late bookers decide, and is being promoted to top of nav | **In Design** | Unknown | Conversion rate of the late availability page against site average | Interest |
| 12 | Mobile PDP layout optimisation | Reviews, group size and map are below the fold on mobile | **To do. RICE rank 1** | Both, day skew | Mobile PDP to availability-check rate. Highest reach and lowest effort combination on the list at 4 days | Interest |
| 13 | Personalisation, related tours, compare, recently viewed | Algolia-based. Customers compare with spreadsheets and tabs today | **To do** | Both | Tours viewed per session against the 52% of multi-day buyers who view 2 or more before purchase | Interest |
| 14 | Local specific content and copy | UK is 72% of US demand and the copy still addresses a first-time visitor to Scotland | **To do. RICE rank 2** | Both, UK skew | UK conversion rate against US. UK ABV is £181 against USA £226 | Interest |
| 4 | Persist user passengers and dates across session | Inputs are lost when navigating between tours | **Scoping** | Both | Repeat availability-check rate within a session | Interest |

**Confidence flags in this phase.** Persist passengers and dates sits at 0.5 on one annoyance report
and is not directly tested. Late availability sits at 0.5 with the persona marked "To discover",
because that segment has never been interviewed. PLP data structure sits at 0.6 on qualitative
reports of filter failure with no instrumentation behind them.

**The sequencing point to make in the room.** Mobile PDP and local content are RICE ranks 1 and 2, at
4 days and 2.5 days, and both sit near the bottom of the delivery order. Navigation and Direct
Packages sit at the top of the delivery order and mid-table on RICE because they cost 20.5 and 23
days. That is not an argument for resequencing, since both are in QA and in build and both carry
dependencies. It is an argument that the two cheapest evidenced wins on the list are being
under-served.

---

## Desire

This specific tour, and whether it can be trusted to work.

| # | Initiative | Focus | Status | Track | Proposed measure of success | Tracker phase |
|---|---|---|---|---|---|---|
| 2b | Introduce guide module on PDP | 2 to 3 guide profiles per PDP. The guide drives roughly 90% of experience quality and is invisible on the page | **In Design.** Blocked on guide content from operations | Both | PDP to availability-check rate on pages with the module against pages without | Desire |
| 2c | Surface accommodation details on tour page | Move accommodation type, price range and included attractions out of the booking flow | **In Design** | Multi-day | Reduce the 60% drop at the accommodation step by moving the qualification decision upstream | Desire |
| 3 | Buy Box redesign | From price, booking options, end dates | **In Design.** Effort TBC, RICE pending | Both | Availability-check rate. Needs a baseline pull | Desire |
| 3a | Add from price | Customers cannot see cost before selecting passengers, dates and options | **In Design** | Both | As above | Desire |
| 3b | Add booking options | Route customers into the right journey after the availability check | **In Design** | Both | Mis-routed journey starts. Not currently measured | Desire |
| 3c | Add end dates on calendar | Show the tour's full date range on selection | **In Design. RICE rank 3** | Multi-day | Support contacts asking whether two tours fit together. Cheapest well-evidenced item on the list at 1.5 days | Desire |
| 10b | Owned reviews | Move from the thin Trustpilot feed to verified attributed post-tour reviews | **To do. RICE rank 4** | Both | PDP exit rate at the review module. Two Segment D participants independently lost confidence there and one moved to a firm no | Return |
| 15 | Pre-released, cancelled and new-date tours | No way to register interest in a tour with no published dates | **To do. RICE rank 8** | Multi-day skew | Registered-interest volume, then conversion from notification | Desire |

**Confidence flags in this phase.** No Buy Box usability study has ever been run, so all three Buy Box
sub-tasks sit at 0.5 with personas inferred rather than tested. Owned reviews carries the highest
confidence on the entire list at 0.95, and its 15-day effort is a Sunny Lemons placeholder for
"Large" rather than a developer estimate. Confirm that before quoting rank 4 as final.

---

## Book

From availability check to payment taken.

| # | Initiative | Focus | Status | Track | Proposed measure of success | Tracker phase |
|---|---|---|---|---|---|---|
| 2 | Direct packages 2.0 | Multi-day booking flow. Phase 2, under the current engagement | **In Build** | Multi-day | Reduce the 60% drop at accommodation and the 60% drop at personal details | Desire |
| 2a | Booking flow optimisations | Accommodation step, personal details form, progress indicator, summary panel | **In Build.** User testing required before design to confirm root cause of both drops | Multi-day | As above, split by step | Desire |
| 9 | Deposits | Multi-day tours currently require full payment upfront | **In Design.** Effort TBC, scoped separately by Stuart | Multi-day | Checkout to purchase rate on multi-day. The drop here is a commitment problem, not a discovery problem | Desire |
| 10a | Auth, shortlisting, deposits and booking management | Account infrastructure is fragmented and carries a known security risk | **To do.** 25 days, RICE rank 9. Depends on Deposits completing | Both | Account creation rate at booking, then repeat login | Return |

**The evidence gap that matters most here.** Deposits sits at 0.55 with no persona assigned. Every
participant in the evidence base is either post-booking or comparison-stage. No site or cart
abandoners have ever been interviewed, so nothing confirms that deposits would recover abandoned
bookings specifically. Segment B remains scoped and not recruited, and it is the single research gap
that would most change the confidence ratings across this whole list.

---

## Pre-tour

Between payment taken and the day of the tour.

**Nothing on the UX backlog.** There is a pre-tour communications section in
`design/account-and-post-booking.md` and no tracker row behind it.

Two documented failures sit in this phase with no initiative against them. Months of silence between
booking and accommodation confirmation, with one customer going back through her email to check the
booking was real. Silence reads as nothing happening, and this persona will delegate logistics only
if the process visibly feels managed. Second, end-of-tour drop-off logistics are unclear when a tour
ends in a city other than the one it started in.

The private tours work lands almost entirely in this phase and in the enquiry stage before it.
`strategy/2026-09_private-tours-service-model.md` carries eight ranked outcomes, seven of which need
no website change. The tracker has no home for them, which is a gap in the tracker rather than in the
work. Do not convert them into build rows to make them fit. Summarised for the day in
`work/2026-09-21_workshop-private-tours-summary_v1.md`.

**Owner on the day.** Rabbie's operations and CRM, with Liberandum on lifecycle. Sunny Lemons has one
design document and no initiative.

**Proposed measure.** Time from booking to accommodation confirmation on multi-day. Inbound contacts
asking whether a booking is confirmed. Neither is currently reported.

---

## Tour

The day itself.

**Nothing on the UX backlog, and this is the phase carrying the strongest single finding in the
research.** The guide accounts for roughly 90% of experience quality by the post-tour customer's own
attribution, and driver-guides are one of only two genuine differentiators Rabbie's has. The other is
depth of service on logistics and accommodation. Small group size, no driving and flexible commitment
are category parity and should not be claimed as differentiators on the day.

One single-voice finding to log rather than act on: itineraries slightly over-promise. A tour sold as
"fishing villages" plural visited one fishing village and one inland village, and a stop presented as
included turned out to be optional on the day. Tolerated but noticed. This is the only evidence in
the base from a completed tour.

**Owner on the day.** Rabbie's operations. Out of scope for this engagement, and worth ten minutes
because it is the input to both the advocacy phase and the guide module in Desire.

**Proposed measure.** Post-tour satisfaction by guide, which operations may already hold and this
engagement has never seen.

---

## Advocacy

After the tour, and the route back into the funnel for the next customer.

| # | Initiative | Focus | Status | Track | Proposed measure of success | Tracker phase |
|---|---|---|---|---|---|---|
| 10e | Post-tour email and loyalty sequence | No structured post-tour communication, so peak rebooking and review intent is wasted | **To do. RICE rank 5.** 2.5 days | Both | Review submission rate and rebooking rate within 90 days | Return |
| 10d | Referral mechanism | Trusted Returners recruit new high-intent visitors unpaid, with zero infrastructure behind it | **To do. RICE rank 7.** 2.5 days | Both | Referred sessions, then referred bookings | Return |
| 10c | Invite to tour | Group coordination. Confidence 0.3, the lowest on the list | **To do.** Effort TBC | Both | Not ready to scope | Return |

**The hard truth to put on this slide.** The persona underneath all three is the weakest in the set at
65% confidence, and the Spike customer insights pack sized it in July 2026: 89.3% of customers have
booked once, roughly 3% of any year's bookers return the following year, and Spike's own segmentation
counts 1,346 Loyal customers at six or more bookings against 281,902 First Timers. Roughly half of
apparent second bookings are the same holiday split into two transactions, and 37 to 41% of second
bookings are made on the same day as the first. P3 is real and it is very small.

All three initiatives are cheap, which was already the argument for doing them and is now the only
argument. Nothing expensive should be built on this persona.

**The blocker nobody has picked up.** Email permission on new bookers is 8.05% in 2026. A retention
programme cannot run against a base that cannot be emailed, and the cause is still unknown: either a
tracking convention change or a real consent collapse. It is cheap to establish and nobody has asked.
This belongs in the room on the 23rd, because it gates the retention half of the UK market bet.

**One measurement caveat for this phase.** Average PAX per booking runs 1.59 to 2.13 across the four
major markets, and group payment mechanics split one organiser's decision across several
transactions. A 16-person decision can present as 16 single-passenger bookings. Nobody has checked
whether it does, and the check is cheap: group transactions by shared departure, date and lead booker.

---

## Cross-phase, and not placeable in one

| # | Initiative | Focus | Status | Proposed measure of success |
|---|---|---|---|---|
| 16 | Research and persona programme | Research sits inside individual initiatives rather than being resourced as a programme, so evidence gaps get carried into build | **In Design.** Enabler, not RICE scored | Number of initiatives below 0.6 confidence, currently five. Target is zero before build |
| 17 | UX design system | Components are built per initiative and drift between templates | **In Design.** Enabler, not RICE scored. Depends on IA page structure being agreed | Share of new components drawn from the library rather than built custom |
| 11 | Customer support improvements | Central help and support page. Timezone-aware North American coverage was asked for | **To do.** Effort TBC, confidence 0.4 | Contact volume by reason, which is not currently categorised |
| 6 | Research the european bookers | Italy has the highest search volume for US and Canada and those pages have never been evaluated | **In Design.** Aug 2026 to mid-Sep, 5.5 days. **Status needs confirming, the sync date is 05/09** | Findings delivered, gaps closed |
| 7 | Research PVT | Private tour motivations and barriers | **Delivered 18/09/2026.** 6 participants, all converted | Delivered. Output is a service model, not website initiatives |

**Design system is the one to watch.** Templates for homepage, PLP, PDP, landing page and late
availability are all in scope across initiatives 1 and 8, with no shared component definition. The
cost of not doing this grows as those land, and component library abandonment is a governance problem
rather than a technical one.

---

## What this list does not contain

Stated plainly so the room does not mistake the backlog for the journey.

- **No initiative in four of the eight phases.** Pre-awareness, awareness, pre-tour, tour.
- **No agreed success measure on any initiative.** Every measure above is proposed.
- **No effort estimate on nine of 17**, including Landing page templates, Buy Box and Deposits.
- **No evidence from anyone who left.** Segment B, site and cart abandoners, is scoped and not
  recruited. Non-booker research is explicitly outside the original commission and should be treated
  as a separate one.
- **No product catalogue items.** The 3 to 4 day mid-length duration gap is described as the highest
  long-term revenue opportunity on the account and is a Rabbie's decision, not a website initiative.
- **No sizing for the group and organiser behaviour.** R1 The Appointed Organiser changes the brief
  on four process changes and none of them is a website feature.

---

## The contractual measure, for the closing slide

A 1% or better improvement in conversion rate, achieved through evidence-based design decisions,
multi-market user insight, and systematic customer experience optimisation. The working measures
underneath it are reduced abandonment across interest and desire, first-time visitors reaching the
right tour without prior brand knowledge, qualification friction moved upstream onto the PDP, the
four personas adopted as the shared frame across all three agencies, and decisions traceable to
evidence with evidence strength stated.
