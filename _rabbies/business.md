# Business: Rabbie's

How Rabbie's makes money. Distinct from `engagement.md`, which covers the commercial terms of your
work with them. Read this before any CRO or UX recommendation.

Mark every item `[stated]`, `[observed]`, or `[assumed]`. Keep actual figures out unless needed;
point to where they live instead.

**Read the gaps as findings.** Most of this file is unknown, and the unknowns cluster in exactly the
places that determine whether the funnel work is aimed correctly. That is itself the most useful
thing here.

**Revised 17/09/2026 against the Spike Insight customer insights pack**, presented 08/07/2026 and
consolidated September 2026, transcribed at `analysis/sep-2026-rabbies-customer-insights-data.md`.
It draws on 608,121 individuals and 722,086 bookings from 2012 to 2026, worth £169.1m. It closes
four gaps in this file outright and narrows two more. It closes none of the cost, margin or capacity
gaps, because it is an analysis of the customer and booking database and there is no cost data in
it. Where a figure below now has a source, the source is named. Figures are still kept to the
minimum needed to make the point.

**Revised 24/09/2026 against the State of the Nation deck**, presented at the all agency session,
transcribed at `work/sep2026_state-of-the-nation_rabbies_performance.md`. Trading data YTD P1 to P8.
It narrows the revenue mix gap, states the fixed cost base for the first time, sizes private tours,
and adds departure hub performance. It also discloses a tracking bug, 11/05/2026 to 22/09/2026, that
misattributed Paid revenue to Direct and Organic. That compromises the paid media figures this file
previously recorded as observed. Each affected line is marked below. Figures marked "derived" are
calculated here from a variance and a percentage, both rounded on the slide, so treat them as
approximate.

---

## Revenue model

- **[observed]** Tour bookings sold per seat, across day tours and multi-day tours. Scotland,
  Ireland, England, Wales and Europe.
- **[observed]** Day tours are around 80 in every 100 sales. Unit share, not revenue share. Source:
  time-in-market deck, Aug 2026.
- **[observed]** Private tours exist and are sold, with at least one documented enquiry-to-booking
  path. Volume and revenue share unknown.
- **[observed] Added 24/09/2026.** Private tours are a material line, not a side product. £3.9m on
  the books YTD, +24% year on year, -28% against budget. 2027 forward book +116.5% against same time
  last year, the largest forward gain of any line in £. Source: State of the Nation, slides 2 and 6.
  This supersedes "volume and revenue share unknown" above.
- **[stated]** Multi-day carries the higher transaction value. The persona work describes the
  Meticulous Planner as the highest average transaction value, and the time-in-market deck says
  multi-day "carries the value". Neither states a figure.
- **GAP.** Revenue split across multi-day, day tours, and private or group charter. Not held.
- **[observed] Added 24/09/2026, gap narrowed.** Revenue against budget by line, YTD P1 to P8: Single
  Day -6% (-£655k, +9% YoY), Multi Day -20% (-£2.4m, -3% YoY), Private -28% (+24% YoY). Total -14%
  against budget, +3% against last year. Source: State of the Nation, slide 2. Derived from those
  variances: Single Day roughly £10.3m and Multi Day roughly £9.6m YTD. If that holds, multi-day
  earns about the same revenue as day tours from around a fifth of the sales. That is the strongest
  support yet for the `[stated]` multi-day value claim above, and it is still a derivation. Ask for
  the actual figures before quoting it.
- **GAP.** Which product lines carry margin, and the size of the differential. Not held.

**Why this matters most.** A conversion lift on day trips and a conversion lift on multi-day are not
the same result. If margin sits in multi-day and the funnel work improves day-trip conversion, the
reported win can be a margin loss.

**This gap was recorded as structural. It is narrower than that, and the correction is actionable.**
Sales are not tagged by product *in GA4*, which is what the August deck's data fix request is about.
Behavioural product split there has to be inferred from which pages a user viewed before booking,
which double-counts anyone who looked at both, and since day tours are most of sales, every
"multi-day" cohort is mostly day tour buyers. That still holds.

**[observed]** The booking database is a different system and it does carry product identity. Spike
cuts bookings by tour duration in days, by tour code, and by named tour. So a revenue split by
duration exists and can be asked for. It would not give behavioural attribution, and it would not
give margin, but it would close the revenue-share question without waiting on the GA4 fix. Nobody
has asked. This is the cheapest open item in the file.

## Unit economics

- **[observed]** Revenue per session by tour is known and tracked, from 12 months of GA4 data. Top
  tours run roughly £4.50 to £7.60 per session. Several high-traffic tours convert far below that:
  North Coast 500 at £1.81, Isle of Arran day tour at £2.32, Glenfinnan Viaduct at £0.75.
- **[observed]** Multi-day: 13 in 100 viewers reach the basket, and 13 in 100 of those pay. Day
  tours: 14 in 100 reach the basket, 38 in 100 pay. Edinburgh tours only, no date range on the
  export. Re-pull before quoting externally.
- **[observed]** Acquisition cost is rising and is measured. Google return on ad spend on non-brand
  campaigns fell from 9.8 to 4.3, January to July 2026. Meta cost per booking rose from £17 to £49,
  May to July, against the same months last year. First visits rose from 51% to 77%.
  **Compromised, flagged 24/09/2026.** A tracking bug from 11/05/2026 to 22/09/2026 misattributed Paid
  revenue to Direct and Organic. Rabbie's own proof is that platform conversion rate fell 54% while
  GA4 conversion rate stayed roughly flat. The Meta figure falls entirely inside the bug window and the
  Google figure partly inside it. Both overstate the decline by an unknown amount. Do not quote either
  again until re-pulled for the corrected period. The 51% to 77% figure has no stated date range and
  may or may not be affected. Source: State of the Nation, slide 3.
- **[observed] Added 24/09/2026.** Direct performance against target, YTD, on the same slide: ROAS
  £16.93 against £22.14, cost per booking £15.84 against £13.56, paid spend £706k against £605k. These
  sit inside the bug window too. They show acquisition getting dearer, but by less than the August
  figures suggested.
- **[observed] Added 24/09/2026.** Direct conversion rate is 1.68% YTD against a 1.87% target.
  Direct bookings 48,841, +1% on last year. This is the baseline the contracted "1% or better
  improvement" is measured against, and the SOW wording does not say whether 1% is relative (1.68% to
  about 1.70%) or absolute (1.68% to 2.68%). Those are two very different contracts. Source: State of
  the Nation, slide 3.
- **[observed] Added 24/09/2026.** US converts at 2.4 times the UK rate. YTD, US 962,233 sessions,
  17,849 bookings, 1.86%. UK 869,116 sessions, 6,786 bookings, 0.78%. US is 42.6% of Direct bookings,
  UK 16.2%, Canada 8.9%, Australia 3.9%. The remaining quarter or so of Direct is not broken down
  anywhere in the project. Source: State of the Nation, slide 4. GA4 basis, so less exposed to the
  tracking bug than the platform figures. See `assumptions.md` A19.
- **[observed]** Average booking value is known at market and channel level. Blended it is roughly
  £234, derived here from £169.1m across 722,086 bookings rather than printed in the deck. By market:
  UK £181, USA £226, Australia £271, Canada £310. Source: Spike, sections 2 and 9.
- **[stated] Added 24/09/2026, reported by Joe.** The three largest funnel losses: tour page to
  checkout 82% (desire), guest details to payment 53% (booking), listing page to tour page 52%
  (interest). Blended across day tours and multi-day, date range not stated. Joe's working reading of
  the 53% is accumulated doubt landing at the commitment point, not a guest details page problem.
  Recorded as `assumptions.md` A21. Split by product before sizing any fix: on the Edinburgh export
  multi-day loses far more between checkout and payment than day tours do.
- **GAP, narrowed.** ABV by product line is still not held. See the duration cut note above, which is
  the route to it.
- **[observed]** Mean party size by market: Australia 1.59, UK 1.79, Canada 1.99, USA 2.13, 2024 to
  date. Source: Spike, section 38.
- **GAP, narrowed.** That is a mean, not a distribution, and it may understate group-led demand.
  Group payment mechanics split one organiser's decision across several transactions, observed in
  2 of 6 private tour bookers. See `assumptions.md` A15. A 16-person decision can present as 16
  single-passenger bookings.
- **[observed]** Repeat booking rate is now measured, and it is weak. 89.3% of customers have booked
  once. Roughly 3% of any year's bookers return the following year. UK is the worst market at 83.6%
  booking once, against 76.0% for Canada and 76.9% for Australia. Source: Spike, sections 40, 41, 43.
- **[observed]** Repeat value is falling, not just repeat volume. Where a second booking is a genuine
  return rather than the same holiday, it is now worth 9.8% less than the first, and that gap has
  widened each year since 2023. The cohort value multiplier has fallen from 1.166 on the 2015 cohort
  to 1.044 on 2024. Source: Spike, sections 47 and 50.
- **[observed]** Roughly half of apparent second bookings are the same holiday split in two, and
  37 to 41% of second bookings are made on the same day as the first. Source: Spike, sections 44 and
  45. Any retention figure quoted externally needs this stripped out first.
- **[observed]** The top 20% of customers drive 65% of revenue. Source: Spike, section 51.

**Do they know their own numbers?** Better than this file previously recorded, and the pattern has
changed. Channel and tour-level performance is well instrumented and actively reviewed: monthly
marketing performance reviews, revenue per session by tour, return on ad spend and cost per booking
by platform. As of July 2026 they also hold a full customer database analysis covering ABV, repeat
rate, cohort value, channel split and affluence profiling. What is still absent is anything with a
cost in it: margin by line, cost per departure, load factor.

Practical consequence: their briefs are reliably grounded when they concern channel, a named tour,
or customer value. They should be verified when they concern product mix, capacity, or margin. The
distinction to hold is that Rabbie's now knows a great deal about what customers are worth and still
nothing recorded here about what they cost to serve.

**Caution on vintage.** The Spike pack is a July 2026 snapshot of a database going back to 2012. It
describes the base, not the current trading period, and several of its cuts stop at 2025 or run part
way into 2026. Do not quote it as a current-year figure.

## Cost structure

- **[assumed]** Largely fixed per departure. A guide, a vehicle and a scheduled slot cost
  approximately the same at four passengers or sixteen. This is the standard shape for scheduled
  small-group operators and is consistent with the maximum-16 model, but it has not been confirmed
  by Rabbie's.
- **[observed]** Multi-day carries a variable accommodation cost with a concierge fee charged to the
  customer. Customers report confusion about what the fee covers. The accommodation itself is booked
  with approved partners after the tour booking.
- **GAP.** Confirmation of the fixed-per-departure assumption.
- **[stated] Added 24/09/2026.** Management describes the business as running on a fixed cost base.
  The 2026 focus is "driving as much volume as we can from the inventory we've already secured, every
  incremental booking adds revenue and profitability against our fixed cost base." Source: State of
  the Nation, slide 6. That moves the assumption above from assumed to stated. It is still not
  confirmed by any cost figure, and the marginal cost gap is untouched.
- **GAP.** Marginal cost of an additional passenger.
- **GAP.** Whether the concierge fee is a margin line or a cost recovery.

**The Spike pack closes none of this.** It is an analysis of the customer and booking database.
There is no cost line anywhere in it. Every cost gap above is exactly where it was.

**Why the gap matters.** If costs are fixed per departure, incremental passengers on
already-scheduled tours are close to pure margin, and load factor matters more than total bookings.
That would change what the funnel work should optimise for, and would make the low-conversion
high-traffic tours a different kind of problem: not wasted traffic, but unsold seats on departures
already running.

## Capacity

- **[stated]** Maximum 16 passengers per tour. Cited by every participant in the booker research as
  the defining reason to choose Rabbie's. It is a brand promise as much as a capacity figure.
- **[observed]** Some tours have no available departures. The research includes a participant unable
  to find dates for a tour she wanted, and a Glenfinnan Viaduct page with no departure attached
  still receiving 1,049 sessions.
- **GAP.** Seats per departure in practice, departures per week, by season.
- **GAP.** Which routes and dates sell out, and when.
- **GAP.** Current load factor, overall or by route.
- **[observed] Added 24/09/2026.** Departure hub revenue is diverging. Against budget: Edinburgh +7%
  (+£691k), Inverness +18% (+£286k), Bristol and Bath +23% (+£138k). Against same time last year:
  Glasgow -5%, London -11%, Dublin -12%, Europe -17%, Manchester -23%. Source: State of the Nation,
  slide 2. The two groups use different bases, budget and last year, so they cannot be ranked against
  each other. Derived: Edinburgh alone is roughly £10.6m YTD, which makes it the business's centre of
  gravity by a wide margin. Hub is where a tour departs, not everywhere it goes. It is the closest
  proxy held for a Scotland and non-Scotland split and it is not that split.
- **[observed] Added 24/09/2026.** Lead time varies by departure hub from roughly 28 to over 150
  days. The slide's values could not be reliably matched to hub and product in transcription, so no
  hub-level figure is recorded here. Ask for the source, Customer Insights Full Analysis p.28.

**The constraint that traps CRO work.** If popular departures already sell out in peak season,
converting more traffic to those dates achieves nothing. The lever becomes shifting demand to
under-filled departures, shoulder season, or less popular routes, which is merchandising rather than
checkout.

**This is the single most important unknown in the file, and July's data did not touch it.** The
Spike pack counts bookings, not seats, so it cannot speak to load factor. The 1% conversion target in
`engagement.md` is written as though conversion is the constraint. Nobody has established whether it
is. Confirm load factor before scoping any further conversion work against peak.

## Seasonality and cash

- **[observed]** Booking lead time is measured and the distribution is known. About 2% of bookings
  are made 293 days out. 5.6% by 100 days. 28.2% by 50 days. 69.3% by 10 days. Only about 17 in 100
  book a month or more ahead. Source: User Timeline Analysis.
- **[observed]** Multi-day books earlier than day tours, but most multi-day booking still happens
  inside the final 100 days. The split is by pages viewed rather than by product bought, so the real
  difference is probably larger.
- **[observed]** Australia books earlier than other markets, under different spend timing.
- **[observed]** Payment is currently in full at booking on multi-day. A 25% deposit option is being
  scoped, delivery projected around October 2026.
- **[observed]** Seasonal demand patterns exist and are used in merchandising: Outlander tours track
  TV release cycles, whisky tours peak in autumn. Nav curation is reviewed quarterly against this.
- **[observed]** Booking seasonality is known and it is remarkably flat. March is the peak at 10 to
  11% of bookings, December the trough at 5 to 6%, consistent across 2023 to 2025. Source: Spike,
  sections 15 and 19. Longer durations skew earlier in the year: 7 day tours took 23% of their 2025
  bookings in January.
- **This is booking month, not travel month.** It does not describe operational seasonality, which
  is still not held. Do not read it as when the tours run.
- **GAP.** Cancellation terms. Noted in the research as not surfaced prominently in the booking
  flow, and never documented.
- **GAP.** Freeze periods when site changes cannot ship. Not established, and it should be before
  test scheduling.

**Why lead time matters for test design.** With 69.3% of bookings inside 10 days, a four-week test
captures most day-tour decisions and only a fraction of multi-day ones. Attribution windows need to
differ by product, and a multi-day test read on a four-week window will systematically understate
the effect.

**Lead time divergence, raised 17/09/2026 and resolved 18/09/2026.** Spike reports average lead
times of 38.8 days for the UK, 67.9 USA, 77.8 Canada and 85.2 Australia, 2024 to date, source
section 37. Those means look irreconcilable with a distribution in which 69.3% of bookings happen
inside 10 days. They are not in conflict. The two describe different populations, and the short
observed window is a property of the traffic Rabbie's acquires rather than of how the market
decides. Paid acquisition weighted to the final weeks selects for people already close to purchase,
so the site sees a late deciding population because that is the population being bought. The
qualitative evidence shows consideration running for months, and specifically so on multi-day.

The practical consequence is that **the GA4 lead time distribution describes Rabbie's direct traffic
mix, not its market.** Do not quote it as customer behaviour. It is a statement about media buying.
Recorded as `assumptions.md` A17, which supersedes A2 and states the cheapest remaining test: GA4
lead time for direct multi-day bookings alone. If that comes back as short as the blended figure,
the late window is real for the product that carries the value and the argument changes.

## Distribution

- **[observed]** Direct site is the channel the engagement works on. Viator, GetYourGuide and
  TripAdvisor all appear in the research as discovery and booking routes.
- **[observed]** Discovery is overwhelmingly third-party: Reddit, TripAdvisor, Rick Steves, Facebook
  groups, personal recommendation. Cold acquisition from search alone is rare in the booker sample.
  Rabbie's owns almost none of the surfaces where customers form their shortlist.
- **[observed]** In-destination marketing exists, including rack cards and van visibility. It
  catches visitors already on the ground and misses those researching from home.
- **[observed]** Channel split is now known, by volume and by value, and it has shifted
  structurally. Direct has overtaken Agent and runs 51 to 57% of bookings since 2023. Agent has
  collapsed from around 54% in 2015 to 8 to 9%. OTA has grown from near zero before 2021 to 35 to
  40%. Source: Spike, section 16.
- **[observed]** Value does not follow volume, and the gap is wide. From 2023 onwards, of roughly
  £90.5m, Direct took 63.5%, Agent 20.3% and OTA 16.2%. Average booking value by channel: Agent
  £635, Direct £323, Concierge £138, OTA £123. Source: Spike, sections 24 and 25. Shares derived
  here from the printed values.
- **[observed] Added 24/09/2026.** B2B is the fastest growing line this year, +12% against budget,
  while Direct is -18% against budget, £13.7m booked with a £2.9m gap. Management expected Direct to
  lead growth and it did not. Source: State of the Nation, slides 2 and 3. Read alongside the OTA and
  agent value split below, and note the Reachability consequence: B2B growth is growth in customers
  who cannot be emailed.
- **GAP.** Commission rates on indirect channels. This is now the only thing standing between the
  file and a real channel margin picture, which makes it the highest-value single number to ask for.
- **GAP.** Whether phone bookings are material. Several research participants said they would phone
  when a page did not answer a question, so the channel is at least in use as a fallback.

**No longer unexamined, and the shape is not what the intuition suggests.** This file previously
recorded channel mix as the largest lever and entirely unexamined. The first half may still be true.
The second is not, as of July 2026.

Three things follow, and the third is the one to hold.

**OTA is a volume channel, not a value channel.** 40% of bookings in 2026, 16.2% of value since
2023, at an ABV of £123 against Direct's £323. Recovering an OTA booking to direct is worth less per
booking than the volume share implies, though it is still worth the commission.

**Agent is small and disproportionately valuable.** 9% of bookings, 20.3% of value, at an ABV of
£635, nearly double Direct. The channel the business has been losing for a decade is the one selling
the largest transactions.

**[assumed] The channel ABV spread is probably product mix showing through channel, not a channel
effect.** An agent selling a 10 day tour and an OTA selling a day tour would produce exactly this
pattern. If that reading is right, this is the strongest evidence the project holds that multi-day
carries the value, which is currently only a `[stated]` item at the top of this file. It would also
mean the agent decline is a multi-day demand problem wearing channel clothing. Nobody has checked
what agents actually sell. The duration cut named in the revenue model section would settle it, and
this is the second reason to ask for it.

**What is still missing.** Commission rates, and therefore margin by channel. Also phone and trade,
which do not appear as separate sources. Spike's source categories are Agents Online, Api, API,
Booking System and Website, and a Concierge line appears in the ABV cut at £138 but not in the
volume split. Whether Booking System is the call centre is not established. Ask.

## Reachability

- **[observed]** Email marketing permission on new bookers has collapsed. It ran at 96 to 99% on
  every cohort from 2015 to 2020, then fell to 15.4% in 2021 and has not recovered. 2026 to date is
  8.05%. Source: Spike, section 10.
- **[observed]** It is almost entirely a channel effect. Over the last three years, website bookings
  are 97.8% marketable and every other source is close to zero, with API at 0.03% and Agents Online
  at effectively nil. Source: Spike, section 11. The OTA and agent growth recorded above is
  therefore also a growth in unreachable customers.
- **[stated]** Spike's own caveat on the slide is that either the convention for tracking
  permissions changed in 2021 or the permission policy changed. They do not know which.

**Why this belongs in a business file rather than a marketing one.** The repeat rate finding above
argues for retention work. This is the thing that would block it. 288,135 customers sit in the
Lapsed segment, larger than the entire active base, and most of the recent ones cannot be emailed.
Any recommendation that routes through CRM needs this checked first.

**Verify before acting, and treat the cause as unknown.** If the 2021 break is a tracking convention
change, a large part of the base may be reachable and mislabelled, and the fix is a data one. If it
is a real consent collapse, the fix is a collection one at the point of booking. The two lead to
completely different work and the evidence does not currently separate them. This is the second
cheapest open item in the file.

- **[stated] Added 24/09/2026, confirmed by Joe.** Customers who have booked can be emailed with
  offers for further tours before they travel. This is separate from the 8.05% general marketing
  permission above, which remains undiagnosed. Keep the basis documented and an opt-out in every
  email.

**Regulatory flag.** Marketing to this base engages UK PECR and UK GDPR, and the soft opt-in
position for existing customers is narrower than it is often assumed to be. Do not advise on what
can be sent to whom without checking the current ICO position. Flagged, not advised on. Owner
unassigned.

## Competitive position

- **[observed]** Two genuine differentiators: driver-guides, and depth of service on logistics and
  accommodation. Small group size, no driving, and flexible commitment are category parity, though
  small group size is the most cited reason customers give for choosing Rabbie's.
- **[observed]** Lost business documented in research: a 5-day Highland tour booked with a
  competitor after no 2-night option was found; a 13-guest private group that went elsewhere after
  Facebook groups suggested Rabbie's did day tours only; a competitor who won partly by asking for a
  deposit and explaining why.
- **[observed]** Alternatives customers actually weigh: self-drive (rejected on road anxiety),
  private driver (cost), large coach tours (experience), Go Ahead and EF Tours, Viator and
  GetYourGuide, and increasingly a travel agent as an alternative route to the whole trip.
- **[observed]** Contradicting the stated view: UK is now 72% of US demand, up from 54%, while US
  non-brand demand is down 40% year on year. The site still addresses UK customers as first-time
  visitors to Scotland.
- **GAP.** Rabbie's own stated view of who they lose to and on what. Never captured directly.

---

## What actually moves their P&L

**Cannot be established from what is held.** Stating that plainly is more useful than an assessment
built on the assumptions above.

Three candidates, in the order the available evidence supports them:

1. **Load factor on scheduled departures.** If the fixed-cost-per-departure assumption holds,
   incremental passengers on running tours are close to pure margin, and the high-traffic
   low-conversion tours are unsold seats rather than wasted spend. Requires the cost structure and
   capacity gaps to be closed.
2. **Channel mix.** Half tested as of July 2026. The volume and value split is known and the
   picture is counter-intuitive: OTA is 40% of bookings and 16% of value, Agent is 9% of bookings
   and 20%. What is not known is commission, so the margin consequence of a channel shift still
   cannot be calculated. One number away from being answerable.
3. **Product mix and when each product is marketed.** Best evidenced of the three. Multi-day reaches
   the basket as often as day tours and converts at a third of the rate, and multi-day demand forms
   months earlier than current spend timing reaches it.

Headline conversion rate sits below all three, and is the thing the engagement is contracted on.

## What they believe moves it

- **[stated]** Conversion rate. The SOW success measure is a 1% or better improvement in conversion
  rate, achieved through evidence-based design decisions and systematic CX optimisation.
- **[stated]** Deposits. Prioritised by the Rabbie's board over other dev work, which is the
  clearest signal in the account of where leadership thinks the constraint sits.
- **[observed]** Late-window paid acquisition. Where the largest spend goes, though the August
  review shows returns from it falling.
- **[stated] Added 24/09/2026.** Management attributes the Direct miss to "softer market confidence,
  a later-booking market and OTA growth". A later-booking market is the opposite reading to
  `assumptions.md` A17, which holds that late booking is produced by late targeting. Neither side has
  run the test that separates them: GA4 lead time for direct multi-day bookings alone. This is now a
  live disagreement with the client's own explanation of their year, not just an internal assumption.
- **[stated] Added 24/09/2026.** On markets, management's line is "quality, not volume, is the
  lever", on the US converting at 2.4 times the UK rate. That runs against the UK bet in
  `assumptions.md` A18, now superseded by A19.
- **[stated] Added 24/09/2026.** 2027 focus: "Scaling Scotland, growing Multi Day, and understanding
  our target markets and the opportunity within them so we can leverage this. Alongside supporting
  non Scotland growth for the future." Multi-day is named as an early focus because it is the weakest
  2027 forward gain, +32.2% against same time last year. Source: slide 6. "Scaling Scotland" is not
  defined by metric.

## The gap

Two divergences, and they point the same way.

**Conversion rate versus product mix.** The contract measures a single site-wide conversion figure.
The evidence says day tours and multi-day are different funnels with different loss points, and that
a site-wide figure dominated by day tours can improve while multi-day, which carries the value, does
not. A win against the contracted metric is achievable without moving the thing that matters.

**Conversion rate versus when demand is reached.** The engagement is scoped on what happens once
someone is on the site. The time-in-market work argues a substantial share of the loss happens
before that, because multi-day demand forms 6 to 12 months out and spend arrives in the final three
weeks.

**How to read their briefs.** A brief framed as a conversion problem may be a mix problem, a timing
problem, or a capacity problem wearing conversion clothing. Ask which product, and ask whether the
departures being optimised for have seats. Neither question is currently answerable from the data
they hold, which is the argument for the four data fixes.

---

## Where the numbers live

| What | Where | Who |
|---|---|---|
| Session and revenue by tour, lead time distribution | GA4 | Rabbie's, Liberandum |
| Return on ad spend, cost per booking, channel performance | Monthly marketing performance review | Michelle, Marketing Director |
| Basket and checkout funnel | GA4 export, Edinburgh only so far | Liberandum, Sarita |
| Testing and CRO results | VWO | Liberandum |
| Backlog, effort, delivery status | monday.com | Rabbie's MarkComm |
| Deposit scope and projected dates | Separate scoping exercise | Stuart |
| Commercial strategy and trading plan | Not seen | Alex, CGO |
| Channel split by volume and value, ABV, repeat and cohort value, affluence profiling | Spike Insight customer insights pack, Jul 2026. Transcribed at `analysis/sep-2026-rabbies-customer-insights-data.md` | Spike, via Rabbie's |
| Revenue against budget by line and hub, Direct KPIs, US and UK conversion, 2027 forward book | State of the Nation deck, Sep 2026, YTD P1 to P8. Transcribed at `work/sep2026_state-of-the-nation_rabbies_performance.md` | Rabbie's, from trading data and Board Report |
| Margin, capacity, load factor, commission rates | **Not held anywhere in the project** | Ask Alex |

**The four data fixes requested in the August deck**, which would close several gaps above:
cross-device recognition, an Apple versus Chrome comparison to size the tracking distortion, product
tags on sales, and analysis of people who did not book.

**Three things to ask for, added 17/09/2026, in order of value against effort.**

1. **Revenue and ABV split by tour duration, from Spike.** The booking database already carries it.
   It closes the revenue mix gap, tests whether multi-day genuinely carries the value, and tests
   whether the agent ABV premium is a product effect. One request, three answers. Ask Spike through
   Rabbie's, not Liberandum.
2. **Commission rates by indirect channel.** The last number between this file and a channel margin
   picture. Ask Alex.
3. **Margin per departure, private against scheduled, at current load factor.** Logged as
   `assumptions.md` A16 and in `notes.md` 17/09/2026. Blocks any recommendation to grow private tour
   volume. Ask Alex.

**Item 1 above is partly answered as of 24/09/2026.** Revenue by line against budget is now held
from the State of the Nation deck, so the revenue share question is largely closed by derivation.
ABV by duration and the agent product mix are not. Revised ask: revenue and ABV by tour duration and
by destination, which also serves the 2027 Scotland and non-Scotland split.

Last reviewed: 24/09/2026
