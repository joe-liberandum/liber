# Workshop opportunities, mapped to the initiative backlog

**Date:** 24/09/2026
**Author:** Joe Collingwood, Sunny Lemons
**Status:** Draft v4, for discussion with Liberandum, then Michelle and Alex. Not agreed.
**Sources:** All agency workshop post-it wall, September 2026 (`+RB_ All_agency_workshop_sep 2026_post_it_notes.md`); State of the Nation deck (`sep2026_state-of-the-nation_rabbies_performance.md`); initiatives tracker synced 05/09/2026 (`initiatives.md`); product data architecture case v2; booker and private tours research; `2026-09-24_2027-delivery-plan_v1.md` for phases.
**Boundary:** Votes show what the room cared about, not what the customer data ranks. Where the two disagree, the data should win. Scores and effort sizes are Sunny Lemons estimates, not developer estimates.

**Version note, v4.** Supersedes v3 of the same date. v4 leads with the 17 initiatives on the existing tracker, not with the workshop opportunities. For each one it shows which workshop problems it already tackles, what the workshop adds, and whether it moves forward, holds, moves back, is re-scoped or is split. It then sets out the evolved sequence and the new work that has no home on the current tracker. The workshop opportunities, scores and ranked list from v3 follow as Part 2, unchanged apart from the removal of v3's "What this does to the tracker" and "This quarter" sections, which Part 1 replaces.

**Version note, v3.** Added business value, customer value and effort scores, a priority score and a ranked list. Later amended the same day to add intended outcomes.

**Version note, v2.** Every post-it assigned to one opportunity. Items classified and labelled. Product data added as the foundation. Removed an unsourced FTE figure and corrected the guide claim.

---

# Part 1 · The original plan, tested against the workshop

## The answer, up front

The 2026 plan still stands. The workshop confirms it and extends it. It does not overturn it.

- **More than half the room's votes, 173 of 314 (55%), land on problems an existing initiative already tackles.** The most-voted initiative is Direct Packages 2.0 and its sub-tasks, at 66 votes. It is already in build.
- **No workshop problem argues against any initiative on the tracker.** The original top four in the delivery order (navigation, Direct Packages, Buy Box, persisting dates and passengers) all stay in the first two phases.
- **The other 141 votes sit where the backlog was never aimed.** The 2026 plan was built for the interest and desire phases of the website, where about 92% of drop-off sits. The workshop added the time between booking and travel, booking more than one tour, product data and operations, and market-level marketing. Those are gaps in coverage, not errors in direction.
- **Three initiatives change shape, for reasons that come mostly from new data rather than from the workshop.** Initiative 5 is re-scoped into a product data foundation. Initiative 10 is split, so the security fix, referral and owned reviews stop waiting on the account build. Initiative 14 keeps its work but loses its UK-first rationale.
- **Four initiatives move later:** landing page templates, the customer portal and account build, customer support, and compare. **Eleven items move earlier,** led by accommodation on multi-day tour pages, the guide module and the mobile tour page.

The framing has moved as well as the list. The 2026 plan aimed at site-wide conversion. The 2027 focus asks for more seats sold on departures already running, multi-day growth, and profit. Every initiative below is re-read against that.

**A limit on the "confirms" claim.** The backlog was prepared as workshop input (`2026-09-21_workshop-initiatives-by-journey-phase_v1.md`). Where the room saw it, the overlap is corroboration from people who knew the plan, not an independent test of it. The customer research behind the original initiatives remains the stronger evidence.

---

## How the workshop votes land on the existing plan

Each post-it is counted once, against the initiative that most directly tackles it.

| Initiative | Workshop votes | Post-its | What the room raised |
|---|---|---|---|
| 2. Direct packages 2.0, with its sub-tasks | 66 | 10 | Accommodation invisible until the booking flow, too many accommodation scenarios, guides not visible, too many booking steps |
| 10. My New Account | 26 | 5 | Portal and the insecure manage-booking page, shortlist, save for later, recommend a friend |
| 5. Improve PLP data structure | 23 | 5 | Filters, tour cards, decision fatigue, destination detail |
| 3. Buy Box redesign | 15 | 3 | Availability on the tour page, seats left, sale price |
| 13. Personalisation, related tours, compare | 11 | 2 | Compare, propensity data |
| 4. Persist passengers and dates | 8 | 1 | The site forgets preferences and dates |
| 1. Navigation and IA | 7 | 4 | Too much choice, one template for every tour type, page layouts, assumed destination knowledge |
| 8. Landing page optimisations | 6 | 1 | Market and need-specific landing pages |
| 9. Deposits | 5 | 1 | Split payment not visible |
| 14. Local specific content | 5 | 1 | US SEO and market content |
| 7. Research PVT | 1 | 1 | Private seekers browsing scheduled tours |
| **On existing initiatives** | **173** | **34** | |
| **No existing home** | **141** | **34** | See "New work with no home on the tracker" |
| **Total** | **314** | **68** | |

**Six initiatives drew no votes:** 6 (European bookers research), 11 (customer support), 12 (mobile tour page), 15 (pre-released and cancelled tours), 16 (research programme) and 17 (design system). So did three sub-tasks: end dates on the calendar, owned reviews and post-tour email. Silence on the wall is not evidence against them. Mobile tour page and owned reviews are the two best-evidenced items on the tracker, at RICE rank 1 and at confidence 0.95.

---

## Each initiative, what the workshop adds, and where it moves

**Movement key.** Each initiative, or each part of a split initiative, takes exactly one.

| Movement | Meaning |
|---|---|
| **Forward** | Starts earlier than the original delivery order implied |
| **Held** | Stays where it was. The workshop confirms it or adds nothing new |
| **Back** | Starts later, with the reason stated |
| **Re-scoped** | Same problem, materially larger or different scope |
| **Split** | Parts separated so they can move independently |
| **Delivered** | Complete. Successor work named |

**Phases** follow the 2027 delivery plan. Phase 0 is October 2026, measure and decide. Phase 1 is October to December 2026, ready for the January multi-day booking peak. Phase 2 is January to June 2027, build. Phase 3 is July to December 2027, scale.

### 1. Navigation redesign, customer mental model
**Original:** delivery priority 1, RICE rank 6, in QA. **Workshop:** 7 votes. OP-02.4.

The workshop confirms the problem: too much choice, and pages that assume the visitor knows the geography. It adds one thing: tour page templates by tour type, so day tours and multi-day tours stop sharing one template.

| Part | Movement | Phase | Why |
|---|---|---|---|
| Navigation launch | Held | 1 | In QA. Nothing in the workshop changes it |
| IA restructure | Held, extended | 2 to 3 | Adds templates by tour type (OP-02.4). They depend on tour type data from the product data foundation |

### 2. Direct packages 2.0
**Original:** delivery priority 2, RICE rank 11, in build. **Workshop:** 66 votes, the most of any initiative. OP-03, OP-04.1, OP-05.5.

This is the strongest confirmation of the original plan. The room put accommodation opacity at the top of the wall, which matches the 60% drop-off at the accommodation step. The workshop adds a sequencing point the original plan did not have: operations should cut the number of accommodation scenarios **before** the selector is built around them (OP-03.1).

| Part | Movement | Phase | Why |
|---|---|---|---|
| Surface accommodation details on tour page | **Forward** | 1 | Rank 4 of 52 on the workshop scoring. Multi-day is the 2027 priority and books from January |
| Introduce guide module on PDP | **Forward** | 1 | 11 votes. Still needs a named operations owner for guide content |
| Accommodation shown earlier, on cards and landing pages | Held, extended | 3 | New scope from the workshop (OP-03.3). Depends on the product data foundation |
| Direct Packages rollout | Held, now gated | 2 | Waits on the accommodation scenario decision (OP-03.1) |
| Booking flow optimisations | Held | 2 | Test before build, as the tracker already requires |

### 3. Buy Box redesign
**Original:** delivery priority 3, effort TBC, in design. **Workshop:** 15 votes. OP-05.1, OP-05.2.

The workshop confirms the Buy Box as the place for price and availability questions, and adds three things to it: availability, seats left and sale price. All three need live data from Traverse.

| Part | Movement | Phase | Why |
|---|---|---|---|
| Add end dates on calendar | **Forward** | 1 | RICE rank 3, 1.5 days. Cheapest well-evidenced item on the tracker |
| Add from price | Held | 2 | Opens with the deposit messaging change |
| Add booking options | Held | 2 | Evidence gap unchanged, confidence 0.5 |
| Availability, seats left, sale price | Held, extended | 2 | New scope (OP-05.1, 05.2). Scarcity and was/now claims need a check against the current CMA position |

### 4. Persist user passengers and dates across session
**Original:** delivery priority 4, scoping. **Workshop:** 8 votes. OP-07.1.

Held, Phase 2. The workshop turns a single-participant annoyance into an 8-vote problem. That strengthens the case without changing the scope. Confidence can move up from 0.5 at the next tracker review.

### 5. Improve PLP data structure
**Original:** delivery priority 5, blocked on the July CRO test. **Workshop:** 23 votes directly, and it sits under OP-01.

**Re-scoped.** The original initiative was right about the cause: the frontend lacks the tour data that filters and cards need. What has changed is the size. The same root cause drives the ecommerce team's manual workload (50 to 65% of their time, estimated), the wrong-market links, the 79 of 120 products with no crawlable listing link, and the availability and seats-left data the Buy Box now needs. The fix becomes a new parent initiative, the **product data foundation**, and the original listing page work is its first use. Its block on the July CRO test is removed.

| Part | Movement | Phase | Why |
|---|---|---|---|
| Attribute definition | **Forward** | 1 | Unblocks the scope and the 2027 funding case (OP-01.3) |
| Traverse to CMS pipeline | Re-scoped, new parent | 2 to 3 | OP-01.4. 110 of 314 votes depend on it in whole or part |
| Filters on the new attributes | Held | 2 to 3 | The original initiative's goal, delivered on the new foundation (OP-02.3) |

### 6. Research the European bookers
**Original:** delivery priority 6, in design, August to mid-September. **Workshop:** no votes.

Held, Phase 0. It now has a sharper job. Its findings feed Rabbie's decision on how much 2027 effort non-Scotland gets (OP-10.6), which the 2027 focus leaves open.

### 7. Research PVT
**Original:** delivery priority 7. **Delivered 18/09/2026.** **Workshop:** 1 vote. OP-11.

Delivered. The successor is the private tours service model, which needs almost no website change. The workshop's one private tour note, people browsing scheduled tours when they want a private one, is partly answered by the research already. New since the research: private tours are £3.9m year to date and the 2027 forward book is up 116.5%. Growth stays gated on a margin comparison against filled scheduled seats (`assumptions.md` A20).

### 8. Landing page optimisations
**Original:** delivery priority 8, in design. **Workshop:** 6 votes. OP-10.3.

**Split.**

| Part | Movement | Phase | Why |
|---|---|---|---|
| Improving late availability functionality | **Forward** | 2 | Late availability is unsold seats close to departure, the most direct seat lever on the tracker. Research on late bookers comes first, because that segment has never been interviewed |
| Overall templates | **Back** | 3 | Templates by market and need depend on the market decision (OP-10.6) and on the product data foundation. Building them first means building them twice |
| Private tours | Delivered via 7 | - | Superseded by the private tours research and service model |

### 9. Deposits
**Original:** delivery priority 9, in design, projected October 2026. **Workshop:** 5 votes. OP-05.3.

Held, Phase 1. The workshop adds that split payment has to be visible, not just available. That belongs in the Buy Box messaging that deposits already opens. The evidence gap on whether deposits recover abandoned bookings is unchanged.

### 10. My New Account
**Original:** delivery priority 10, to do, depends on Deposits. **Workshop:** 26 votes. OP-07.3, OP-08.5, OP-08.6, OP-09.3.

**Split.** The original bundle holds five different things behind one dependency. The workshop shows three of them should not wait.

| Part | Movement | Phase | Why |
|---|---|---|---|
| Remove or secure the old manage-booking page | **Forward**, split out | 0 | A known security risk. It should not wait for deposits or a new portal (OP-08.5) |
| Owned reviews | **Forward**, split out | 2 | Confidence 0.95, the highest on the tracker. Needs no account |
| Referral mechanism | **Forward**, split out | 2 | 7 votes. A prompt at confirmation needs no account (OP-09.3) |
| Post-tour email and loyalty sequence | Held | 2 | Runs after the new pre-tour sequence (OP-08.3). Blocked on the email permission question |
| Auth, shortlisting, deposits and booking management | **Back** | 3 | 25 days. Shortlisting merges with compare from 13. The security part is already split out |
| Invite to tour | **Back** | 3 | Confidence 0.3, the lowest on the tracker. No workshop support |

### 11. Customer support improvements
**Original:** delivery priority 11, to do, confidence 0.4. **Workshop:** no votes.

**Back**, Phase 3. Its likeliest job, telling customers what happens after they book, is now done more cheaply by the post-booking work (OP-08.1). Review whether a central help page is still needed once that is live.

### 12. Mobile PDP layout optimisation
**Original:** delivery priority 12, RICE rank 1, 4 days. **Workshop:** no votes.

**Forward**, Phase 1. Nothing in the room raised it, and nothing weakens it. Most paid social traffic is mobile, and paid cost per booking is behind target. It is the cheapest cost-to-sell lever on the tracker, and the original tracker already flagged it as under-served.

### 13. Personalisation, related tours, compare, recently viewed
**Original:** delivery priority 13, RICE rank 12. **Workshop:** 11 votes. OP-06.1, OP-07.2, OP-07.3, OP-07.4.

**Split.**

| Part | Movement | Phase | Why |
|---|---|---|---|
| Related tours | **Forward**, extended | 1 | Moved to the post-booking moment as cross-sell on the confirmation page and email. 37 to 41% of second bookings happen the same day as the first (OP-06.1) |
| Recently viewed | Held | 2 | Cheap. No dependency |
| Compare | **Back** | 3 | Needs like-for-like attributes from the product data foundation. Merges with shortlisting from 10 |
| Personalisation | Held, reframed | 2 | Becomes a decision on data ownership and consent first (OP-07.4) |

### 14. Local specific content and copy
**Original:** delivery priority 14, RICE rank 2. **Workshop:** 5 votes. OP-10.1.

Held, Phase 2. The work stands, and the rationale changes. The original case was UK growth. The US now converts at 2.4 times the UK rate, and Rabbie's own line is quality over volume (`assumptions.md` A19). The initiative becomes market-specific copy, market by market, not UK first. Its RICE rank should be re-scored on that basis, and its effort data issue still needs resolving.

### 15. Pre-released, cancelled and new-date tours
**Original:** delivery priority 15, RICE rank 8, 4 days. **Workshop:** no votes.

**Forward**, Phase 2. Registering interest in a tour with no dates turns a lost customer into a booking on a departure once it is scheduled. Under the 2027 seat focus, that moves it up.

### 16. Research and persona programme
**Original:** enabler. **Workshop:** no votes.

Held. The next sprint is late availability bookers, the segment behind the late availability page and one of three with no persona. Research with non-bookers and abandoners remains the largest gap and a separate commission.

### 17. UX design system
**Original:** enabler. **Workshop:** no votes.

Held, ongoing. The workshop adds work that needs components: tour cards, accommodation blocks, guide profiles, USP blocks, templates by tour type. Its case is stronger than it was.

---

## Summary of movement

| Movement | Items |
|---|---|
| **Forward** | 2 accommodation on tour page, 2 guide module, 3 end dates, 5 attribute definition, 8 late availability, 10 security fix, 10 owned reviews, 10 referral, 12 mobile tour page, 13 related tours as cross-sell, 15 pre-released and cancelled tours |
| **Held** | 1 navigation and IA, 2 Direct Packages rollout and booking flow, 3 from price and booking options, 4 persist dates, 5 filters, 6 European research, 9 deposits, 10 post-tour email, 13 recently viewed and personalisation, 14 local content (reframed), 16 research, 17 design system |
| **Back** | 8 overall templates, 10 account build and invite to tour, 11 customer support, 13 compare |
| **Re-scoped** | 5 into the product data foundation |
| **Split** | 8, 10, 13 |
| **Delivered** | 7 Research PVT |

That is 11 items forward and 5 back. None of the moves back reverses a judgement in the original plan. Each waits on something the workshop or the new data made visible: the market decision, the product data foundation, or cheaper work that now does the same job.

---

## New work with no home on the tracker

141 of the 314 votes. These are where the plan has evolved rather than where it was wrong. They cluster in the journey phases the backlog never covered.

| Cluster | Votes | Workshop items | Proposed tracker treatment |
|---|---|---|---|
| Booking more than one tour | 34 | OP-06.2 finance decision, OP-06.3 basket, OP-06.4 bundles | **New initiative:** multi-tour basket, Phase 3, after the finance decision in Phase 0 |
| Booking to travel | 30 | OP-08.1 what happens next, 08.2 email links, 08.3 post-booking sequence, 08.4 day-before SMS | Two tasks in Phase 1, two small projects in Phase 2. Proposed as one tracker parent, "Booking to travel", so the phase has an owner |
| Capturing intent and CRM | 20 | OP-09.1 permission cause, 09.2 basket audit, 09.4 rebook offer, 09.5 lead capture, 09.6 CRM owner | Tasks and one small project. 09.1 in Phase 0 gates the rest |
| Product data and ecommerce operations | 18 | OP-01.1 time log, 01.2 locale question, 01.4 pipeline | Inside the new product data foundation parent |
| Markets and paid media | 15 | OP-10.2 locale prefixes, 10.4 search programme, 10.5 paid split, 10.6 non-Scotland decision | Led by Salience and paid media, not tracker rows. 10.6 is a Rabbie's decision in Phase 0 |
| Differentiation and ad content | 12 | OP-04.2 USP block, 04.3 ad creative | Two tasks, Phase 1 |
| Everything else | 12 | OP-05.4 currency, 02.1 listing order, 04.4 multi-day map, 12.1 and 12.2 ways of working | Currency as a small project in Phase 2. The rest are decisions or depend on the foundation |

**Two new parent initiatives in total:** the product data foundation, absorbing 5, and the multi-tour basket. Everything else fits under an existing parent, runs as a task or small project, or is a decision.

---

## The evolved sequence

The original delivery order, then where each item now sits. Existing initiatives are numbered. New work is shown by its workshop reference.

| Phase | Existing initiatives | New work |
|---|---|---|
| **0 · Oct 2026** Measure and decide | 10 manage-booking security fix. 6 European research findings into the non-Scotland decision | Nine decisions given owners. Accommodation scenarios (03.1), finance restriction (06.2), listing order (02.1), non-Scotland (10.6). Ecommerce time log (01.1). Email permission cause (09.1) |
| **1 · Oct to Dec 2026** Ready for January | 1 navigation launch. 2 accommodation on tour pages and guide module. 3 end dates. 9 deposits with split payment visible. 12 mobile tour page. 13 related tours as confirmation cross-sell. 5 attribute definition | USP block (04.2). What happens next (08.1). Email links (08.2). Tour card copy (02.2). Locale prefixes (10.2). Ad creative (04.3) |
| **2 · Jan to Jun 2027** Build | 2 Direct Packages rollout and booking flow. 3 from price, availability, seats left, sale price. 4 persist dates. 8 late availability, after research. 10 owned reviews, referral, post-tour email. 13 recently viewed. 14 market-specific copy. 15 register interest. 5 pipeline build starts | Post-booking sequence (08.3). Day-before SMS (08.4). CAD and AUD currency (05.4). Paid split by product and market (10.5) |
| **3 · Jul to Dec 2027** Scale | 1 templates by tour type. 2 accommodation on cards and landing pages. 5 filters on new attributes. 8 overall templates. 10 account build, shortlisting. 13 compare. 11 customer support review | Multi-tour basket (06.3). Save for later (09.5). Search programme (10.4). Multi-day map and destination detail (04.4) |

**What still holds from the original plan's logic.** Navigation and Direct Packages stay first because they are in flight and carry dependencies. Qualification moves upstream onto the tour page. Day tours and multi-day are treated as different products. Cheap and reversible comes before designed features. The research programme closes evidence gaps before build. Each of those principles is unchanged, and several of the moves above apply them more strictly.

**What has evolved.** The measure moves from site-wide conversion to seats sold on running departures, multi-day revenue and cost to sell. The scope moves from the website's interest and desire phases to the whole journey from booking to travel. And product data moves from a listing page fix to the foundation most of the plan stands on.

---

## Where the original plan needs correcting, not just extending

Stated so it is not found later by someone else.

1. **Initiative 14's rationale no longer holds.** The UK growth case is now low confidence. The work stays, reframed by market.
2. **Initiative 10 put a security fix behind a dependency chain.** It should never have waited on deposits.
3. **Initiative 5 was blocked on the wrong thing.** A CRO test cannot unblock a data structure problem.
4. **The plan had no measure beyond conversion.** Margin, load factor and commission are still not held anywhere in the project. Until they are, "more profitable" can only be judged by stand-ins.

---

# Part 2 · Workshop opportunities in detail

Unchanged from v3, including scores, ranks, types, labels and intended outcomes.

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

## How items are scored

Three scores per item. The priority score is value divided by effort.

**Business value, 1 to 5.** Effect on Rabbie's revenue, cost or risk, weighted to the 2027 focus.

| Score | Meaning |
|---|---|
| 5 | Moves multi-day or Scotland revenue with evidence of size, removes a material cost or risk, or unblocks a new initiative |
| 4 | Clear commercial effect on a 2027 focus area, size not yet known |
| 3 | Useful commercial effect, indirect or on a smaller line |
| 2 | Minor commercial effect |
| 1 | Hygiene. Little direct commercial effect |

**Customer value, 1 to 5.** How much it removes a problem customers actually hit, and how close that problem sits to a known drop-off point. Internal process items score 1 by definition, because customers never see them. Their value shows up in business value.

| Score | Meaning |
|---|---|
| 5 | Removes a problem at a measured drop-off point, for example the accommodation step |
| 4 | Removes a problem customers report repeatedly |
| 3 | Improves a step customers pass through, problem reported but not severe |
| 2 | Nice to have for customers |
| 1 | No direct customer effect |

**Effort, t-shirt size.** Elapsed effort across every team involved. For decisions, this is the organisational effort of reaching and implementing the decision. Where the tracker holds a day count, the size follows it.

| Size | Rough size | Points |
|---|---|---|
| XS | Under 2 days | 1 |
| S | 2 to 5 days | 2 |
| M | 1 to 3 weeks | 3 |
| L | 3 to 8 weeks | 5 |
| XL | Over 8 weeks, or a platform change across several teams | 8 |

**Priority score = (business value + customer value) ÷ effort points.** The highest possible is 10, a 5 and 5 item at XS. The lowest is 0.25. Ties are broken by business value, then by smaller effort.

**Evidence is shown but not scored.** The Evidence column states how strong the case behind each item is: Strong, Audited, Directional, Stated, Single voice, Workshop only, or Internal for process items. Items at M or larger that rest on workshop votes or a single voice are marked "(validate first)". They should not move into build on their score alone.

---

## Priority order

| Rank | Ref | Item | Type | Labels | Business | Customer | Effort | Score | Evidence | Gate |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | OP-04.2 | First-visit USP block | Task | Social & Content | 3 | 3 | XS | 6.00 | Directional |  |
| 2 | OP-11.1 | Private tour qualification at first contact | Covered, service model memo | Ops | 3 | 3 | XS | 6.00 | Directional |  |
| 3 | OP-08.1 | "What happens next" after booking | Task | UX, Social & Content | 2 | 4 | XS | 6.00 | Workshop only |  |
| 4 | OP-03.2 | Accommodation content on multi-day tour pages | Covered, init. 2 | Social & Content, UX | 5 | 5 | S | 5.00 | Strong |  |
| 5 | OP-01.1 | Two-week ecommerce time log | Task | Ops | 4 | 1 | XS | 5.00 | Internal |  |
| 6 | OP-03.1 | Cut the accommodation scenarios | Decision | Ops | 5 | 4 | S | 4.50 | Directional |  |
| 7 | OP-08.5 | Remove or secure old manage-booking page | Task | Tech | 5 | 3 | S | 4.00 | Stated |  |
| 8 | OP-01.2 | Products maintained once or per locale | Task | Ops, Tech | 3 | 1 | XS | 4.00 | Internal |  |
| 9 | OP-01.5 | Re-scope initiative 5 into OP-01 | Decision | Tech, Ops | 3 | 1 | XS | 4.00 | Internal |  |
| 10 | OP-09.2 | Audit abandoned basket and retargeting | Task | Paid media, Social & Content | 3 | 1 | XS | 4.00 | Workshop only |  |
| 11 | OP-12.1 | Measure and baseline before scoping | Decision | Ops | 3 | 1 | XS | 4.00 | Internal |  |
| 12 | OP-12.2 | CRO and SEO sequencing rule | Decision | Ops | 3 | 1 | XS | 4.00 | Workshop only |  |
| 13 | OP-04.3 | Ad creative showing a guided vehicle tour | Task | Paid media, Social & Content | 2 | 2 | XS | 4.00 | Workshop only |  |
| 14 | OP-06.2 | Finance restriction on multi-tour booking | Decision | Ops, Tech | 5 | 2 | S | 3.50 | Internal |  |
| 15 | OP-02.1 | Listing order rules, incl. non-Scotland | Decision | Ops, Social & Content | 4 | 3 | S | 3.50 | Directional |  |
| 16 | OP-06.1 | Cross-sell on confirmation, known tour pairs | Extend init. 13 | UX, Social & Content | 4 | 3 | S | 3.50 | Strong |  |
| 17 | OP-10.1 | Market-specific copy | Covered, init. 14 | Social & Content, SEO | 4 | 3 | S | 3.50 | Directional |  |
| 18 | OP-04.1 | Guide profiles on tour pages | Covered, init. 2 | Social & Content, UX | 3 | 4 | S | 3.50 | Directional | Needs ops content owner |
| 19 | OP-09.1 | Cause of the 8.05% email permission rate | Task | Ops, Tech | 5 | 1 | S | 3.00 | Strong |  |
| 20 | OP-05.3 | Split payment visibility | Covered, init. 9 | UX, Social & Content | 3 | 3 | S | 3.00 | Directional | With deposits |
| 21 | OP-10.2 | Remove hand-entered locale prefixes | Task | SEO, Social & Content | 3 | 3 | S | 3.00 | Audited |  |
| 22 | OP-09.6 | Owner for content and CRM journeys | Decision | Ops | 2 | 1 | XS | 3.00 | Workshop only |  |
| 23 | OP-08.2 | Booking emails link to the booked itinerary | Task | Tech | 1 | 2 | XS | 3.00 | Workshop only |  |
| 24 | OP-08.3 | Post-booking sequence by lead time | Small project | Social & Content | 4 | 4 | M | 2.67 | Directional |  |
| 25 | OP-10.6 | Non-Scotland effort and measure for 2027 | Decision | Ops, Paid media, SEO | 4 | 1 | S | 2.50 | Internal |  |
| 26 | OP-09.3 | Referral prompt at confirmation | Covered, init. 10 | UX, Social & Content | 3 | 2 | S | 2.50 | Directional |  |
| 27 | OP-07.2 | Recently viewed | Covered, init. 13 | Tech | 2 | 3 | S | 2.50 | Directional |  |
| 28 | OP-01.3 | Define the product attributes every surface needs | Small project | UX, Tech, SEO, Ops | 4 | 3 | M | 2.33 | Audited |  |
| 29 | OP-05.4 | CAD and AUD currency (validate first) | Small project | Tech | 4 | 3 | M | 2.33 | Workshop only |  |
| 30 | OP-02.2 | Tour card content and copy | Small project | UX, Social & Content | 3 | 4 | M | 2.33 | Directional |  |
| 31 | OP-10.5 | Paid split by product and market, product-tagged conversions | Small project | Paid media, Tech | 5 | 1 | M | 2.00 | Directional |  |
| 32 | OP-03.3 | Accommodation on cards and landing pages | Extend init. 2 | Social & Content, UX | 3 | 3 | M | 2.00 | Directional | After 01.4 |
| 33 | OP-07.1 | Persist passengers and dates | Covered, init. 4 | Tech | 3 | 3 | M | 2.00 | Directional |  |
| 34 | OP-09.5 | Save for later and lead capture | Small project | UX, Tech | 3 | 3 | M | 2.00 | Directional | With 07.3 |
| 35 | OP-09.4 | Segment the rebook offer | Task | Social & Content | 2 | 2 | S | 2.00 | Workshop only | After 09.1 |
| 36 | OP-11.2 | Private route from scheduled pages | Task | UX, Social & Content | 2 | 2 | S | 2.00 | Single voice | After margin comparison |
| 37 | OP-08.4 | Day-before SMS (validate first) | Small project | Tech, Ops | 2 | 4 | M | 2.00 | Workshop only |  |
| 38 | OP-03.4 | Direct Packages rollout | Covered, init. 2 | Tech | 5 | 4 | L | 1.80 | Strong | After 03.1 |
| 39 | OP-02.3 | Filters on the new attributes | Covered, init. 5 | Tech, UX | 4 | 5 | L | 1.80 | Strong | After 01.4 |
| 40 | OP-05.2 | Sale price before and after in buy box (validate first) | Extend init. 3 | Tech, UX | 3 | 2 | M | 1.67 | Workshop only |  |
| 41 | OP-07.4 | Propensity data and ownership | Decision | Tech, Ops | 3 | 2 | M | 1.67 | Internal | After 09.1 |
| 42 | OP-05.1 | Availability and seats left | Extend init. 3 | UX, Tech | 4 | 4 | L | 1.60 | Directional | After 01.4 |
| 43 | OP-05.5 | Fewer steps in the booking flow | Covered, init. 2 | UX | 4 | 4 | L | 1.60 | Strong |  |
| 44 | OP-07.3 | Shortlist and compare | Covered, init. 10 and 13 | UX, Tech | 4 | 4 | L | 1.60 | Directional | Compare after 01.4 |
| 45 | OP-10.3 | Market and need landing page templates | Covered, init. 8 | UX, Social & Content, SEO | 4 | 3 | L | 1.40 | Directional |  |
| 46 | OP-08.6 | Customer portal | Covered, init. 10 | Tech, UX | 3 | 4 | L | 1.40 | Directional |  |
| 47 | OP-10.4 | US, Canada and Australia search programme (validate first) | Small project | SEO | 4 | 2 | L | 1.20 | Workshop only |  |
| 48 | OP-02.4 | Tour page templates by tour type | Extend init. 1 | UX, Tech | 3 | 3 | L | 1.20 | Directional |  |
| 49 | OP-04.4 | Destination detail and multi-day map | Small project | Social & Content, UX, Tech | 3 | 3 | L | 1.20 | Directional | After 01.4 |
| 50 | OP-01.4 | Traverse to CMS product data pipeline | New initiative | Tech | 5 | 4 | XL | 1.12 | Audited | After 01.1 and 01.3 |
| 51 | OP-06.3 | Multi-tour basket | New initiative | Tech, UX | 5 | 4 | XL | 1.12 | Strong | After 06.2 |
| 52 | OP-06.4 | Attraction bundles (validate first) | Small project | Ops, Tech | 3 | 2 | L | 1.00 | Workshop only | After 06.3 |

### What the score cannot see

A value-for-effort score is a planning input, not the sequence. Four things override it.

1. **Gates.** An item cannot start before whatever gates it. The Gate column names each one. The gates that matter most: the accommodation scenarios decision (03.1, rank 6) comes before Direct Packages rollout (03.4, rank 38). The finance decision (06.2, rank 14) comes before the multi-tour basket (06.3, rank 51). The cause of the email permission rate (09.1, rank 19) comes before anything that emails customers with offers.
2. **Enablers.** The product data pipeline (01.4) ranks 50th on its own score. 110 of the room's 314 votes sit on problems it fixes in whole or part, and five other items in this list wait on it. Scored on what it unblocks rather than on what it delivers alone, it would sit near the top. Its inputs, the time log (01.1, rank 5) and the attribute definition (01.3, rank 28), should start now so that the build can be scoped and funded for 2027.
3. **Risk.** The old manage-booking page (08.5, rank 7) is a known security issue. It goes first regardless of rank.
4. **Lead time.** The two XL items, the data pipeline and the multi-tour basket, take longest to land. If either is wanted in 2027, planning has to start this quarter even though both rank near the bottom.

### Where this disagrees with the tracker's RICE

Accommodation content on tour pages ranks 4th here. On the tracker it is a sub-task scored 0.450 and not separately ranked. The difference is that this score counts the 60% drop-off at the accommodation step and the 2027 multi-day focus directly. Direct Packages 2.0 is RICE rank 11 on the tracker and 38th here. Both scores agree it is valuable and expensive. Neither list should be resequenced without looking at the other.

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

**Intended outcome.** Product data entered once and correct everywhere, with ecommerce time moved from data entry to merchandising.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-01.1 | Two-week time log splitting first-pass entry from rework, per locale | A measured figure for ecommerce hours on product data replaces the 50 to 65% estimate, so the pipeline has a costed business case | Task | Ops | Now |
| OP-01.2 | Establish whether each product is maintained once or once per locale | We know whether each product change is made once or three times, which sets the size of the saving | Task | Ops, Tech | Now |
| OP-01.3 | Define the attributes every surface needs: duration, destination and region, tour type, stops, accommodation, departure hub, market pricing, availability | Tech can scope the pipeline against one agreed list of what every page needs, so one build serves listing pages, tour pages, the Buy Box and SEO | Small project | UX, Tech, SEO, Ops | Now |
| OP-01.4 | Traverse to CMS pipeline, so product data is entered once | Product data is entered once and shown correctly everywhere. Fewer hours on data entry, fewer wrong or missing product details for customers | New initiative | Tech | Next, after OP-01.3 |
| OP-01.5 | Re-scope initiative 5 into OP-01 and remove its block on the July CRO test | The data work is funded and run as a platform initiative, no longer held behind a listing page CRO test | Decision | Tech, Ops | Now |

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

**Intended outcome.** Visitors find a tour that fits sooner, and listing pages sell what Rabbie's most needs to sell.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-02.1 | Merchandising rules for listing order, including where non-Scotland and low-ranking tours sit | Listing pages lead with the tours Rabbie's most needs to sell, such as under-filled departures and chosen non-Scotland tours, instead of defaulting to Scotland best sellers | Decision | Ops, Social & Content | Now |
| OP-02.2 | Tour card content and copy that does not assume destination knowledge, within current data | First-time visitors can tell tours apart from the card alone and move to a tour page without knowing the geography | Small project | UX, Social & Content | Now |
| OP-02.3 | Filters rebuilt on the new attributes | Customers find a tour that fits their dates, length and interests through filters, and fewer give up searching | Covered by initiative 5, now inside OP-01 | Tech, UX | Next |
| OP-02.4 | Tour page templates by tour type (day, multi-day, private) and layout flexibility | Each tour type's page answers the questions that type raises: day tours quickly, multi-day in depth | Extend initiative 1, IA restructure, with 17, design system | UX, Tech | Next |

**Measure.** Listing to tour page progression. Filter use leading to a tour view.

---

## OP-03 · Knowing where you will sleep
**49 votes, the largest cluster**

**From the wall.** Accommodation range options (4). Price uncertainty, Direct Packages not everywhere (2). Complicated accommodation scenarios for customers and operations (10). Accommodation not visible until the booking flow (11). Accommodation information on tour pages (8). Accommodation information earlier than the tour page (5). Accommodation too complex, simplify (9).

**Evidence.** 60% drop-off at the accommodation step in the multi-day booking flow. Three participants entered checkout just to find accommodation information. Multi-day is -20% to budget and the weakest 2027 forward gain at +32.2%.

**Sequence matters here.** Cut the scenarios first, then show them, then build the selector. Building Direct Packages' selector around scenarios that are about to be cut is wasted build.

**Intended outcome.** Multi-day customers know where they will sleep before they commit, and fewer abandon at the accommodation step.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-03.1 | Operations decision to reduce the number of accommodation scenarios | Fewer accommodation options to explain, price and operate. Simpler for customers, cheaper to run, and a smaller Direct Packages build | Decision | Ops | Now |
| OP-03.2 | Accommodation type, price range and inclusions on multi-day tour pages | Multi-day customers know where they will sleep and roughly what it costs before they commit, so fewer drop out at the accommodation step | Covered by initiative 2, sub-task "Surface accommodation details on tour page" | Social & Content, UX | Now |
| OP-03.3 | Accommodation shown earlier, on cards and landing pages | Accommodation becomes part of how customers choose a multi-day tour, not a surprise after they have chosen | Extend initiative 2, same sub-task | Social & Content, UX | Next, needs OP-01 |
| OP-03.4 | Direct Packages rollout and price certainty | Customers can see and book accommodation at a certain price on every multi-day tour | Covered by initiative 2, Direct packages 2.0 | Tech | Next, after OP-03.1 |

**Measure.** Drop-off at the accommodation step. Multi-day checkout to purchase, currently 13 in 100 on the Edinburgh export.

---

## OP-04 · Showing what the tour is, and why us
**29 votes**

**From the wall.** Product differentiation (5). Driver-guides not visible on the site (10). Not enough driver-guide content (1). USPs explaining the brand to new visitors (6). Static landscape ad content can read as a walking tour (1). Little detail on destinations, points of interest and attractions (4). One overall map for multi-day rather than a per-day itinerary (2).

**Evidence.** Rabbie's has two genuine differentiators: driver-guides, and depth of service on logistics and accommodation. Small groups and not having to drive are category parity and should not lead. Guide evidence is strong on rebooking and all post-tour. The link from guide visibility to conversion is untested (`assumptions.md` A6, medium). One day-tour customer put roughly 90% of experience quality down to the guide. That is a single voice.

**Intended outcome.** New visitors understand what the tour is and why Rabbie's before they compare on price.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-04.1 | Guide profiles on tour pages | Customers see the driver-guide before they book. Also tests whether guide visibility lifts conversion, which is untested (A6) | Covered by initiative 2, sub-task "Introduce guide module on PDP" | Social & Content, UX | Now, needs a named operations contact for guide content |
| OP-04.2 | First-visit USP block built on the two real differentiators | First-time visitors understand quickly why Rabbie's rather than a coach tour or self-drive | Task | Social & Content | Now |
| OP-04.3 | Ad creative that shows a guided vehicle tour, not a walking tour | People who click an ad already understand it is a guided small-group vehicle tour | Task | Paid media, Social & Content | Now |
| OP-04.4 | Destination and attraction detail, and a whole-trip map for multi-day | Multi-day customers can see where the trip goes and what they will see, and judge whether it is the right route | Small project | Social & Content, UX, Tech | Next, needs OP-01 stop data |

**Measure.** Tour page to availability check, with the guide module against without.

---

## OP-05 · Deciding and paying with confidence
**31 votes**

**From the wall.** No availability information on tour pages (7). Fewer steps and no doubts in the booking flow (6). Split payment options not visible (5). No sale price in the buy box (4). No seats-left indicator (4). Currency only GBP and USD despite Canadian and Australian markets (5).

**Evidence.** Canada has the highest ABV at £310 and Australia £271, and both are asked to pay in a foreign currency. Multi-day converts 13 in 100 from basket to payment against 38 in 100 for day tours.

**Compliance flag.** Seats-left counts and was/now pricing are both regulated claims in UK consumer law. Scarcity must reflect real inventory, and a reference price must be genuine. Check the current CMA position before either ships. Flagged, not advised on.

**Intended outcome.** Customers reach payment with no open questions on price, availability or how to pay.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-05.1 | Availability and seats left on the tour page and buy box | Customers see real availability without entering the booking flow, and stop meeting sold-out dates late | Extend initiative 3, Buy Box redesign | UX, Tech | Next, needs the Traverse feed through OP-01 |
| OP-05.2 | Sale price shown before and after in the buy box | Genuine discounts are visible and trusted at the point of decision | Extend initiative 3 | Tech, UX | Next |
| OP-05.3 | Split payment visibility | Customers who would rather pay in stages know they can before they abandon | Covered by initiative 9, Deposits, and the deposit messaging in initiative 3 | UX, Social & Content | Next, with deposits |
| OP-05.4 | CAD and AUD currency | Canadian and Australian customers see prices in their own currency, in the two highest-value markets | Small project | Tech | Now to scope. Display and charge currency are different builds |
| OP-05.5 | Fewer steps and fewer doubts in the booking flow | More multi-day customers get from basket to payment. Currently 13 in 100 do, on the Edinburgh export | Covered by initiative 2, sub-task "Booking flow optimisations" | UX | Next |

**Measure.** Step completion through the flow. Multi-day checkout to purchase.

---

## OP-06 · Booking more than one tour
**34 votes**

**From the wall.** No basket, one tour per booking because of finance restrictions (16). Cannot book several tours at once, same cause (8). Shortlist several holidays to book together (7). Attraction bundle upsell (3).

**Evidence.** Customers already buy a second tour. We just make them do it twice. 37 to 41% of second bookings are made the same day as the first. Loch Ness, Glencoe and the Highlands is the top second tour after three of the best sellers, at 29 to 31%. More seats sold on departures already running is exactly the 2026 focus: more volume from inventory already secured.

**Intended outcome.** More seats sold per customer, on departures already running.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-06.1 | Cross-sell on the confirmation page and email, using the known first-to-second tour pairs | More customers book their second tour straight away, on departures already running, at no extra acquisition cost | Extend initiative 13, related tours, to the post-booking moment | UX, Social & Content | Now |
| OP-06.2 | Establish the finance restriction and whether any workaround exists short of a basket | A clear answer on what finance allows, so the basket is designed within it or the restriction is changed | Decision | Ops, Tech | Now |
| OP-06.3 | Multi-tour basket | Customers book a whole trip in one transaction. Higher order value and fewer lost second bookings | New initiative | Tech, UX | Next, after OP-06.2 |
| OP-06.4 | Attraction bundles | Higher order value from attractions customers would buy anyway. Validate demand first | Small project | Ops, Tech | Next, after OP-06.3 |

**Measure.** Share of bookings with more than one tour. Second bookings taken in the same session.

---

## OP-07 · Keeping what I found
**25 votes**

**From the wall.** No shortlist (5). No compare (7). Cannot build "My Trip" linking dates and itinerary (1). The site does not remember preferences or dates (8). No aggregated data to serve by propensity (4).

**Evidence.** 52% of multi-day buyers view two or more tours before purchase. Customers compare using spreadsheets, browser tabs and emailed lists of links.

**Intended outcome.** Customers comparing tours over days or weeks can do it on the site and come back to it.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-07.1 | Persist passengers and dates across the session | Customers set dates and party size once and see relevant availability on every tour they view | Covered by initiative 4 | Tech | Now |
| OP-07.2 | Recently viewed | Customers get back to tours they have looked at without searching again | Covered by initiative 13 | Tech | Now |
| OP-07.3 | Shortlist and compare, with "My Trip" as a later extension of the shortlist | Multi-day customers shortlist and compare on the site instead of in spreadsheets and tabs, and come back to finish | Covered, split between initiative 10 (shortlisting) and 13 (compare). Consolidate into one | UX, Tech | Next, compare needs OP-01 |
| OP-07.4 | What customer data should drive propensity, and who owns it | An agreed and lawful data basis for showing customers the tours they are most likely to book | Decision | Tech, Ops | Next, after OP-09.1 |

**Measure.** Tours viewed per session. Return rate to a saved list.

---

## OP-08 · The gap between booking and travelling
**40 votes**

**From the wall.** Not clear what happens next after booking (6). No warm-up or excitement before the tour (10). No SMS for critical information or the day-before pickup, time and guide name (10). No customer portal, and the old manage-booking page needs removing because of security issues (10). No post-purchase flow for long lead-time bookers (4). Email links to a generic tour page rather than the itinerary (0).

**Evidence.** Lead time from booking to travel runs from about 28 days to over 150 depending on departure hub, and averages 85 days from Australia. Multi-day books earlier than day tours. That is months of silence in which we neither reassure nor sell.

**Security flag.** The old manage-booking page is a known security risk. Its replacement currently sits in initiative 10, which depends on Deposits completing. Retiring the risk should not wait for a new portal. Split the two.

**Consent flag.** Booking information messages do not need marketing consent. Upsell content inside them may. Check the PECR position before the post-booking sequence carries offers.

**Intended outcome.** Customers feel looked after from booking to pickup, contact the team less, and buy more before they travel.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-08.1 | "What happens next" on the confirmation page and email | Fewer customers unsure whether their booking is confirmed, and fewer contacts asking | Task | UX, Social & Content | Now |
| OP-08.2 | Point booking emails at the booked itinerary, not the generic tour page | Booking emails take customers to what they actually booked | Task | Tech | Now |
| OP-08.3 | Post-booking email sequence by lead time, multi-day first | Long lead-time customers stay informed and engaged between booking and travel, and some add a second tour | Small project | Social & Content | Now |
| OP-08.4 | Day-before SMS with pickup point, time and driver-guide name | Customers arrive at the right place and time knowing who their guide is. Fewer missed pickups and day-before calls | Small project | Tech, Ops | Now |
| OP-08.5 | Remove or secure the old manage-booking page | The known security risk on the old manage-booking page is closed | Task | Tech | Now, urgent |
| OP-08.6 | Customer portal | Customers manage their own booking, with fewer support contacts and a place to offer pre-tour extras | Covered by initiative 10, sub-task "Auth, shortlisting, deposits and booking management" | Tech, UX | Next |

**Measure.** Inbound contacts asking whether a booking is confirmed. Pre-tour add-on and second-tour bookings made from the sequence.

---

## OP-09 · Capturing intent we currently lose
**30 votes**

**From the wall.** Reduce spend on new customers and focus on retention (Michelle, not voted). No lead generation (3). Rebook offer is one generic code for everyone (6). No save for later or other lead capture in the booking funnel (3). No abandoned basket lead capture and retargeting (4). No recommend a friend (7). Retargeting across Meta, email and web limited to none (4). Marketing content and CRM journeys not joined up (3).

**A contradiction to resolve first.** The State of the Nation deck lists "Built and enhanced abandoned basket" as delivered this year. The wall says it does not exist. Establish what is live before scoping anything here.

**Blocker.** Email permission on new bookers is 8.05% in 2026, against 96 to 99% on every cohort to 2020. Nobody knows whether this is a tracking change or a real collapse in consent. Everything in this cluster that routes through email waits on the answer.

**Intended outcome.** Intent that currently leaves anonymously is captured and can be reached again.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-09.1 | Establish the cause of the 8.05% permission rate | We know whether most recent customers can be emailed, which decides whether CRM-led retention is possible at all | Task | Ops, Tech | Now, gates the cluster |
| OP-09.2 | Audit what abandoned basket and retargeting actually exist, then close the gaps | A factual inventory of the abandoned basket and retargeting that exist, so gaps are closed rather than rebuilt | Task, then extend whatever exists | Paid media, Social & Content | Now |
| OP-09.3 | Referral prompt at confirmation | Happy customers bring friends, and personal recommendation, the main discovery route, becomes visible and measurable | Covered by initiative 10, sub-task "Referral mechanism". Decouple from the account build | UX, Social & Content | Now |
| OP-09.4 | Segment the rebook offer | Rebook offers matched to the customer, lifting redemption without discounting to everyone | Task | Social & Content | Now, after OP-09.1 |
| OP-09.5 | Save for later and lead capture in the funnel | Visitors not ready to book leave a way to reach them instead of leaving anonymously | Small project | UX, Tech | Next, with OP-07.3 |
| OP-09.6 | Single owner for how marketing content and CRM journeys join up | Marketing content and CRM journeys tell one story under one owner | Decision | Ops | Now |

**Paid media caveat.** Paid revenue was misattributed to Direct and Organic from 11/05/2026 to 22/09/2026. Any retargeting baseline from that period needs re-pulling.

**Measure.** Recovered baskets. Referred sessions, then referred bookings.

---

## OP-10 · Speaking to each market properly
**26 votes**

**From the wall.** No market or need-specific landing pages (6). Low brand awareness outside Scotland (1). US SEO (5). Cross-geo signals confusing Google (5). No Canada and Australia focus (4). Not knowing what customers want to target (1). Paid feedback signals dominated by Scotland day tours (3). No paid strategy split between single and multi-day (1).

**Evidence.** The US produces 42.6% of direct bookings at 1.86% conversion. The UK produces 16.2% at 0.78%. Canada and Australia carry the highest ABVs. The audit found at least 48 links sending visitors to the wrong market, all hand-entered. The private tours research found Rabbie's is filed as a Scotland-only company. One participant gave a week of European business to another operator for that reason.

**Changed since the tracker was last scored.** Initiative 14, local content, is RICE rank 2 on the basis that UK growth is the better bet. That belief is now low confidence (`assumptions.md` A19), and management's own line is that quality, not volume, is the lever. The work still stands, but it should be framed market by market, not UK first.

**Intended outcome.** Each market is addressed as it is, and spend follows value rather than volume.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-10.1 | Market-specific copy on the highest-traffic pages | Each market is addressed as it is. UK customers who know Scotland and first-time US visitors get different copy, and conversion rises by market | Covered by initiative 14. Reframe from UK first to market by market | Social & Content, SEO | Now |
| OP-10.2 | Remove hand-entered locale prefixes from content | Visitors stay in the right market with the right prices and content, and search engines get clean market signals | Task. Root fix sits in OP-01 | SEO, Social & Content | Now |
| OP-10.3 | Market and need-based landing page templates | Campaigns launch onto templates built for a market or need, not built from scratch each time | Covered by initiative 8, sub-task "Overall templates" | UX, Social & Content, SEO | Next |
| OP-10.4 | US, Canada and Australia search programme | More non-brand search traffic from the highest-value markets | Small project, Salience's to lead | SEO | Next |
| OP-10.5 | Paid strategy split by product and market, with conversions tagged by product so bidding is not steered by Scotland day tours | Paid spend is steered by the products and markets that matter for 2027, not by Scotland day tour volume | Small project | Paid media, Tech | Now. Check whether the new datalayer already carries product tags |
| OP-10.6 | How much 2027 effort non-Scotland gets, and against what measure | Non-Scotland growth has an agreed level of effort and a measure, so it is resourced on purpose | Decision | Ops, Paid media, SEO | Now |

**Measure.** Conversion by market. Landing page to tour page progression by campaign type.

---

## OP-11 · Private tour intent on the scheduled catalogue
**1 vote, but commercially weighted**

**From the wall.** People who want a private tour also go through scheduled tours. Investigate or test why (1).

**Partly answered already.** In the private tours research, one organiser used scheduled tour pages to learn the destinations and as a price anchor, running a scheduled tour through the passenger selector just to see what her group would cost. Private tours are -28% to budget, +24% year on year, and the 2027 forward book is up 116.5%.

**Gate.** Nothing that grows private volume should be funded until private margin has been compared with filled seats on scheduled departures (`assumptions.md` A20). That comparison does not exist.

**Intended outcome.** Private tour demand is routed and qualified without growing volume before margin is known.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-11.1 | Qualification at first contact: party size, age spread, a named constraint | Group enquiries reach the right product at first contact, and more private enquiries convert | Covered by the private tours service model memo, which needs no website change | Ops | Now |
| OP-11.2 | Private tour route from scheduled tour pages for large parties | Large parties browsing scheduled tours see the private option. Only after the margin comparison | Task | UX, Social & Content | Next, after the margin comparison |

---

## OP-12 · How the agencies work together
**3 votes**

**From the wall.** Not always clear what outcome we expect from a piece of work (2). CRO seems to break SEO and vice versa (1).

Neither is a ticket. Both are rules.

**Intended outcome.** The agencies work to shared outcomes and stop undoing each other's work.

| Ref | Item | Intended outcome | Type | Labels | When |
|---|---|---|---|---|---|
| OP-12.1 | Every opportunity gets one measure and a baseline before it is scoped. The measures above are proposed by Sunny Lemons, not agreed | Every item is judged against a measure and baseline agreed before work starts | Decision | Ops | Now |
| OP-12.2 | A sequencing rule between CRO and SEO changes, with a named owner across Liberandum and Salience | CRO and SEO changes stop undoing each other | Decision | Ops | Now |

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

## Open questions

- Is there a workaround to the finance restriction on booking several tours at once, short of a full basket? OP-06 is blocked on this.
- What is behind the 8.05% email permission rate? It gates OP-09 and the upsell half of OP-08.
- What abandoned basket capability actually went live this year?
- Who in operations owns guide content and the accommodation scenario decision?
- Which of the ecommerce time figures, 50 to 60% or 65%, is closer? Only the time log settles it.
