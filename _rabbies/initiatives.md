# Initiatives

Summary of the 2026 UX initiatives backlog. Source of truth is `Rabbies_2026_UX-initiatives_Tracking.xlsx`, sheet `Initiatives (1)`. This file is the readable version. Where the two disagree, the workbook wins.

**Last synced:** 2026-09-05

**Workbook note.** The file contains two full sheet sets. `Initiatives`, `Values`, `Initiatives Original`, `value`, `RICE methodology`, and the same five again suffixed `(1)`. The `(1)` set is newer: 30 rows rather than 26, adds the two research initiatives, the design system, and replaces the CRO / Design / Tech / Content columns with `Rabbie's owner`, `Supporting teams`, `CRO test`, and `CRO test focus`. Use the `(1)` set. The older set should be deleted once someone has confirmed nothing unique sits in it.

Initiative names below are verbatim from the tracker so they can be matched against it, including source punctuation.

---

## Two orderings, and they disagree

The tracker carries two independent priority columns. Do not conflate them.

**`Priority` (1 to 17)** is the agreed delivery sequence. It reflects dependencies, work already in build, and commitments made.

**`Overall priority rank` (1 to 13)** is the RICE ranking. Value to cost ratio only.

They diverge sharply, and the divergence is the interesting part.

| Initiative | Delivery priority | RICE rank | RICE score |
|---|---|---|---|
| Mobile PDP layout optimisation | 12 | **1** | 2.812 |
| Local specific content and copy | 14 | **2** | 2.240 |
| Add end dates on calendar | 3 (sub-task) | **3** | 1.500 |
| Owned reviews | 10 (sub-task) | **4** | 0.950 |
| Post-tour email and loyalty sequence | 10 (sub-task) | **5** | 0.720 |
| Navigation redesign | **1** | 6 | 0.659 |
| Referral mechanism | 10 (sub-task) | 7 | 0.480 |
| Pre-released, cancelled and new-date tours | 15 | 8 | 0.450 |
| My New Account | 10 | 9 | 0.336 |
| Improving late availability functionality | 8 (sub-task) | 10 | 0.333 |
| Direct packages 2.0 | **2** | 11 | 0.333 |
| Personalisation | 13 | 12 | 0.327 |
| Research the european bookers | 6 | 13 | 0.182 |
| Research PVT | 7 | 13 | 0.182 |

Sub-tasks scored but not separately ranked: IA restructure 0.900, guide module on PDP 0.600, surface accommodation on tour page 0.450.

**How to hold this.** Mobile PDP layout and local content sit near the bottom of the delivery order and top of the RICE order. Both are cheap (4 days and 2.5 days), high reach, and evidenced. Navigation redesign and Direct packages 2.0 sit at the top of the delivery order and mid-table on RICE, because their effort is 20.5 and 23 days. That is not an argument for resequencing. Nav and Direct Packages are in QA and in build, and both carry dependencies. It is an argument that mobile PDP and local copy are being under-served relative to what they would return.

The RICE methodology sheet says it directly: this is a Sunny Lemons planning input, not a substitute for judgement about dependencies, sequencing, or work already in build. Cite the score, then say what sequencing says.

---

## Status vocabulary

`In QA`, `In Build`, `In Design`, `In Review`, `Scoping`, `Blocked`, `To do`.

Current spread: 1 in QA, 2 in build, 11 in design, 2 scoping, 1 blocked, 9 to do.

---

## The backlog

Parent initiatives numbered by delivery priority. Sub-tasks indented under their parent.

### 1. Navigation redesign, customer mental model
**In QA.** Owner Tech. Supporting Content, Ecommerce, Salience. Apr to Aug 2026. All four personas, Desire.
Restructure primary nav around Departure City, Destinations, Duration, Interests, Most Popular. Align with how customers arrive, not how Rabbie's organises its business.
*Evidence.* 74% of homepage visitors use neither nav nor search. Search converts at 23.98%, nav at 18.73%.
*CRO.* Test after launch, on nav label set and category order.
*Depends on.* Salience alignment, URL taxonomy standardisation, landing page readiness.

**Status update 24/09/2026, reported by Joe, not yet reflected in the workbook.** Navigation and IA complete. Navigation is driving more people to listing pages, but listing pages are failing to move them on to tour pages. The constraint has moved from finding a listing page to leaving it. Templates by tour type, the remaining part, moves into the listing page rebuild (LI-12 in `work/2026-09-24_2027-delivery-plan_v4.md`). The before-and-after figure is not yet held.

- **Information architecture restructure.** In Build. Site map, URL structure, page templates for homepage, PLP, PDP, landing page, late availability. Largest single design workstream. Phase it: agree structure first, then templates in traffic order. Not suitable for CRO test, validate via SEO and search metrics.

### 2. Direct packages 2.0
**In Build.** Owner Tech. Jun to Sep 2026. Purposeful Adventurer and Meticulous Planner, Desire.
*Evidence.* 60% drop off at the accommodation step and 60% at personal details in the multi-day booking flow. The accommodation step is doing qualification work that belongs on the PDP.
*CRO.* Test before build, on accommodation step and personal details form.

- **Booking flow optimisations.** Accommodation step refinement, personal details form review, progress indicator, summary panel. User testing required before design to confirm root cause of both drop-offs.
- **Introduce guide module on PDP.** In Design. Owner Content. 2 to 3 guide profiles per PDP. Guide quality is the primary driver of rebooking and the guide is invisible on the current PDP. Blocked on guide content from operations, and a spec is needed so the right content gets gathered.
- **Surface accommodation details on tour page.** In Design. Owner Content. Move accommodation type, price range and included attractions from the booking flow to the PDP. Three participants entered checkout specifically to find accommodation information.

### 3. Buy Box redesign
**In Design.** Owner Ecommerce. From Jul 2026. Desire. **Effort TBC, RICE pending.**
*Evidence gap.* No dedicated Buy Box usability study has been run. Only related signal from booking-flow walkthroughs. Personas inferred, not tested. Confidence 0.5.
Deposit messaging must be updated as part of the deposit scope, which is the opening for the other Buy Box changes.

- **Add from price.** Customers cannot see cost before selecting passengers, dates and options.
- **Add booking options.** Route customers into the right booking journey after the availability check rather than one generic path. Evidence gap, one directional signal.
- **Add end dates on calendar.** Highlight the tour's full date range on selection. 1.5 days, RICE rank 3. Cheapest well-evidenced item on the list.

### 4. Persist user passengers and dates across session
**Scoping.** Owner Tech. Interest. **Effort TBC.**
*Evidence gap.* Not directly tested. One Segment D participant lost inputs when navigating and called it an annoyance. 52% of multi-day buyers view 2 or more tours before purchasing, so the cost recurs across a session. Confidence 0.5.

### 5. Improve PLP data structure
**Blocked** on July CRO test completion. Owner Tech. Interest. **Effort TBC.**
Frontend lacks the tour data needed for reliable filtering and tour cards. Foundational blocker for everything else on the PLP. Customers say filters do not work, and some return visitors gave up looking for tours they had booked before. Tour stop data may be absent from the structure, which also affects SEO and any future compare feature.

### 6. Research the european bookers
**In Design.** Owner Ecommerce. Aug 2026 to mid-Sep. 5.5 days.
Italy has the highest search volume for US and Canada. Those pages have never been evaluated and probably carry the same problems as the Scotland pages, or worse.

### 7. Research PVT
**Delivered as research, 18/09/2026.** Owner Ecommerce. Fieldwork 2 to 16 Sep 2026, 6 participants, all converted. Findings in `research/2026-Q3-pvt/findings.md`, plan closed out in `research/2026-Q3-pvt/plan.md`.
Understand motivations and barriers for private tour bookers. Open question: do they want fully custom tours or private versions of existing ones, and are they a distinct persona or a need held by the existing four.

**Both open questions are answered and neither answer is the one the row anticipated.** Custom against private-version turned out not to be the decision: the product is the same route inventory either way and what separates a good private tour from a poor one is curation. And the buyers are neither a fifth persona nor a need state, they are a role, recorded as R1 The Appointed Organiser in `personas.md`.

**What this initiative hands on is a service model, not a set of website initiatives.** Eight ranked outcomes in `strategy/2026-09_private-tours-service-model.md`, of which seven need no website change. The tracker has no home for that, which is a gap in the tracker rather than in the work. Do not convert them into build rows to make them fit.

**Two questions the study could not answer and a successor would have to.** Where the enquiry to booking handoff loses people, and why groups dismiss Rabbie's before enquiring. Both need non-converting enquirers, which booker-only recruitment cannot reach.

### 8. Landing page optimisations
**In Design.** Owner Content. From Jul 2026. Interest.

- **Overall templates.** **Effort TBC, RICE pending.** Reach 5, impact 3. Likely the largest piece in this group, so scoring the group without it would overstate priority. Landing pages are doing two jobs for two customer types at once, with no repeatable story structure, so every campaign is built from scratch. Cited as a major factor in the 92% interest and desire drop-off.
- **Improving late availability functionality.** 6 days, RICE rank 10. Late availability is being promoted to the top of the nav but the page has not been reviewed for how late bookers decide. **Persona marked "To discover."** Reach scored low precisely because that segment has never been interviewed.
- **Private tours.** Scoping. **Effort TBC.** Interviews, not build. One 13-guest group dismissed Rabbie's for a private booking because Facebook groups suggested day tours only. A documented direct revenue miss. New segment: group and private hire.

### 9. Deposits
**In Design.** Owner Ecommerce. Jul to Oct 2026. Desire. **Effort TBC, being scoped separately by Stuart.**
Multi-day tours require full payment upfront. One participant described a reserve-now-pay-later feature elsewhere as excellent.
*Evidence gap.* All current participants are post-booking or comparison-stage. No site or cart abandoners have been interviewed, so nothing confirms deposits would recover abandoned bookings specifically. Persona not yet assigned. Confidence 0.55.

### 10. My New Account
**To do.** Owner Tech. From Aug 2026. Depends on Deposits completing.

- **Auth, shortlisting, deposits and booking management.** 25 days, RICE rank 9. Account infrastructure is fragmented and carries a known security risk.
- **Owned reviews.** 15 days, RICE rank 4. Highest confidence on the entire list at 0.95. Segment D rated moving beyond the thin Trustpilot feed to verified attributed post-tour reviews as the single clearest conversion blocker. **Effort is a Sunny Lemons estimate, not a dev one.** Source said "Large" with no day count; 15 days is a placeholder. Confirm before relying on the rank.
- **Invite to tour.** **Effort TBC.** Confidence 0.3, the lowest on the list. Evidence gap, inferred from one participant acting as group coordinator.
- **Referral mechanism.** 2.5 days, RICE rank 7. Trusted Returners are the primary acquisition channel for new high-intent visitors and there is currently zero infrastructure for it.
- **Post-tour email and loyalty sequence.** 2.5 days, RICE rank 5. No structured post-tour communication, so the moment of peak rebooking and review intent is wasted.

### 11. Customer support improvements
**To do.** Owner Content. From Jun 2026. **Effort TBC.** Confidence 0.4.
Central Help and Support page. Related signal only: one participant asked for live chat or WhatsApp with timezone-aware North American coverage.

### 12. Mobile PDP layout optimisation
**To do.** Owner Ecommerce. From Jun 2026. All four personas, Interest. 4 days. **RICE rank 1.**
Most paid social traffic is mobile, and mobile buries reviews, group size and map below the fold. High traffic, not converting. Reach 5, impact 3, confidence 0.75, effort 4 days. Effort and evidence both directly sourced.

### 13. Personalisation, related tours, compare, recently viewed
**To do.** Owner Ecommerce. 5.5 days, RICE rank 12. Algolia-based. Customers currently compare manually with spreadsheets and multiple tabs and struggle to re-find tours.

### 14. Local specific content and copy
**To do.** Owner Content. Supporting Salience. 2.5 days. **RICE rank 2.**
UK is now 72% of US demand, but PDP and homepage copy still addresses a first-time visitor to Scotland. UK customers care more about price and trust different signals, ABTA and ATOL rather than the current set.
**Data issue.** Source effort is recorded as "Large / 2 to 3 days," which is internally inconsistent. Confirm actual size before treating rank 2 as final.

### 15. Improving customer experience of pre-released tours, cancelled tours and tours with new dates added
**To do.** Owner Tech. 4 days, RICE rank 8. Customers interested in a tour with no dates, or a cancelled tour, have no way to register interest. They check back manually or book elsewhere.

### 16. Research and persona programme
**In Design. Enabler, not RICE scored.** Owner Ecommerce. Sunny Lemons supporting.

- **Ongoing discovery research.** Research currently sits inside individual initiatives rather than being resourced as a programme, so evidence gaps get carried into build rather than closed before it.
- **Persona build: unvalidated segments.** Late availability bookers, group and private hire, cart and site abandoners. Three segments drive initiatives on this list with no persona behind them, so their reach and impact cannot be estimated with confidence.

### 17. UX design system
**In Design. Enabler, not RICE scored.** Owner Tech. Depends on IA restructure page structure being agreed.
Components are built per initiative, so patterns are rebuilt each time and drift between templates. Templates for homepage, PLP, PDP, landing page and late availability are all in scope across initiatives 1 and 8 with no shared component definition. Cost of not doing this grows as those land.

---

## Evidence gaps register

Nine initiatives carry a named evidence gap. This is the most important thing in the tracker and the easiest to lose when the list is read as a plan.

| Initiative | Gap | Confidence |
|---|---|---|
| Invite to tour | Not tested. Inferred from one participant's group-coordinator behaviour | 0.30 |
| Customer support improvements | Related signal only, not a test of this initiative | 0.40 |
| Buy Box, from price | No Buy Box usability study exists. Personas inferred | 0.50 |
| Buy Box, booking options | No test of this interaction. One directional signal | 0.50 |
| Persist passengers and dates | Not directly tested. One annoyance report | 0.50 |
| Late availability | Persona "To discover." Segment never interviewed | 0.50 |
| Deposits | No abandoners interviewed, so recovery claim is unconfirmed. No persona assigned | 0.55 |
| PLP data structure | Qual reports of filter failure, no instrumentation | 0.60 |
| Private tours | ~~New segment, no persona~~ Role identified, R1, 18/09/2026. Remaining gap is sizing, not understanding | 0.60, held |

Rule: a confidence below 0.6 with an effort of TBC means the initiative is not ready to be scoped, let alone built. Initiative 16 exists to close these. Say so when one of them comes up.

**Private tours confidence is held at 0.60 rather than raised, 18/09/2026, and the reason matters.** The study was commissioned to move this number and it did not, because it closed a different gap from the one the score measures. Motivation and decision pattern are now well understood on 6 participants. What the score needs is sizing, and sizing is blocked twice over: private bookings are not separable in the data, and group payment mechanics split one organiser's decision across several transactions, so average party size cannot be read either. See `assumptions.md` A15. Raising the score on qualitative depth alone would misrepresent what is known.

**Segments with no persona:** late availability bookers, group and private hire, cart and site abandoners. Group and private hire now has a role behind it rather than a persona, R1 in `personas.md`, which is enough to design against and not enough to score reach with.

---

## Effort picture

Scoped effort on the list totals 154 days. Nine initiatives carry `Effort (days): TBC`, including three of the four largest workstreams by likely size: Landing page overall templates, Buy Box redesign, and Deposits.

Any total, any capacity plan, and any RICE-based sequencing argument is provisional until those nine are scoped. State that rather than presenting a total as if it were complete.

---

## Known data issues

1. **Duplicate sheet sets.** Resolve which is canonical and delete the other.
2. **Local content effort.** Recorded as "Large / 2 to 3 days." Contradictory. Drives RICE rank 2.
3. **Owned reviews effort.** 15 days is a Sunny Lemons placeholder for "Large," not a dev estimate. Drives RICE rank 4.
4. **Nine efforts are TBC.** Their RICE ranks read "Pending."
5. **Combined effort figures.** Nav redesign's 20.5 days combines nav and IA restructure. Direct packages' 23 days combines booking flow, guide module and accommodation surfacing. Do not read either as the parent task alone.
6. **Research PVT has no `Problem to be solved` framing tied to site evidence**, unlike every other row. It is framed on business potential. **Resolved 18/09/2026, and the framing was right.** The study found the website close to absent from the private tour decision, with 4 of 6 spending under ten minutes on site before making contact. There was no site evidence to frame it on.
7. **Two initiatives share RICE rank 13.**
