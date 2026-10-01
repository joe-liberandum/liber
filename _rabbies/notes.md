# Notes

Append only running log. Newest at the bottom. Never edit or reorder an earlier entry. If something was wrong, add a new entry correcting it.

**Entry format.**

```
## YYYY-MM-DD | short title

**Did.** What was produced or changed. Name the files.
**Decided.** Decisions made and who made them.
**Open.** What is unresolved, and who owns it.
```

Keep entries short. This is a log, not a report.

---

## 2026-09-05 | Repo set up

**Did.** Created the Claude Code working structure: `CLAUDE.md`, `engagement.md`, `notes.md`, `research/plan.md`, `research/findings.md`, `research/SOURCES.md`, plus folder READMEs for `analysis/`, `design/`, `work/`, `delivered/`.
**Decided.** Raw transcripts stay outside the repo. `research/SOURCES.md` points to them rather than duplicating them.
**Open.** Local paths in `research/SOURCES.md` are placeholders and need filling in. Historic entries below are backfilled from project records and are approximate on dating.

---

## 2026-09-05 | SOW date question resolved

**Did.** Removed the date-check flag from `engagement.md` and replaced it with a "How we got here" section.
**Decided.** The three dates in the SOW are not a conflict. There were two engagements. The 04 August 2025 signature belongs to the earlier Direct Packages project. The January 06 2025 header is a typo for 2026. The current engagement runs from 6 January 2026.
**Open.** Start and end dates for the 2025 Direct Packages engagement still to be confirmed.

---

## Backfill, dates approximate

The entries below reconstruct work completed before this log existed. They are included so the repo carries its own history. Treat the dates as indicative.

## 2025 | Direct Packages engagement

**Did.** Discrete project to improve the Direct Packages booking flow, with user testing support. Phase 1 shipped under this engagement.
**Decided.** Core argument established here and carried forward: the booking flow was doing qualification work that belongs on the PDP.
**Open.** This work led directly to the full year engagement secured for January 2026. Direct Packages Phase 2 sits under that later contract, not this one.

## 2026-04 | Persona and navigation work

**Did.** Four persona model built from the 21 booker dataset. Navigation structure proposal produced, organised around customer intent rather than business geography: Departure City, Destinations, Duration, Interests, Most Popular, New for 2026, Sale.
**Decided.** Four personas adopted as the shared frame across Sunny Lemons, Liberandum, and Salience. No new personas to be created.
**Open.** Research base is bookers only. Non-bookers, cart abandoners, and competitor-only bookers not yet interviewed.

## 2026-06 | Segment D new visitor study

**Did.** Six moderated sessions with new visitors, 3 to 4 June. Findings written up in `segment-d-active-holiday-planners-findings.md`.
**Decided.** Segment D strengthens the Meticulous Planner and Pragmatic Day-Tripper. Confirms the mid-length duration gap. Trusted Returner not testable in this sample by design.
**Open.** "Excludes accommodation" labelling identified as actively misleading. Review section identified as a trust breaking point.

## 2026-06-18 | UK day tour booker interview

**Did.** Single moderated interview and walkthrough with a recent UK day tour customer. Written up in `rabbies-day-tour-booker-findings.md`.
**Decided.** Booking-by-proxy recognised as a real decision path the site does not support. Multi-day continuity, same guide and same group, named as the differentiating claim against the stitched-together anti-pattern.
**Open.** European and Italy search dead-end reclassified as a desire phase conversion risk rather than a usability defect.

## 2026-07 | Customer insight deck

**Did.** `Rabbie's customer insight` deck delivered. Personas with confidence ratings, behaviours, jobs to be done, and friction points.
**Decided.** Sequence by confidence. Build against Meticulous Planner and Pragmatic Day-Tripper now. Treat Purposeful Adventurer and Trusted Returner tests as hypothesis generating.
**Open.** Non-booker research named as the single commission that would most change the confidence ratings.

## 2026-08 | Time in market analysis

**Did.** Combined deck, v4, 28 slides, synergising the time-in-market and booking window analysis with the earlier Scaling Interest marketing recommendation. Source file `rabbies-when-are-customers-in-market.pptx`.
**Decided.** Central argument accepted internally: Rabbie's booking data reflects a late buying strategy that created a self-reinforcing loop, not evidence that customers decide late. Australia used as the natural experiment for earlier booking patterns.
**Open.** Framing line to carry forward: "We are not found late because people decide late. We are found late because late is the only place we look."

---

## 2026-09-07 | All-agency meeting, 23 September

**Did.** Reviewed Michelle's proposed structure for the all-agency meeting on 23 September 2026, hosted by Rabbie's in Edinburgh. Attending: Liberandum, Sunny Lemons, Salience (SEO), Evolution (data layer). Michelle proposed organising the session around channel groupings: Inspire (digital PR, social, brand activity), Attract (paid media across search, social, emerging channels, affiliates), Consider (SEO, AEO, content strategy, technical SEO), Convert (CRO, discovery and landing pages, PDPs, booking flow, checkout, account experience, trust signals), Retain (CRM and lifecycle marketing). Each stage to carry key challenges, insights, opportunities, delivery progress, collaboration needs and next steps.

**Decided.** Nothing agreed yet. Four points of pushback are proposed, not accepted: use the full customer journey structure (pre-awareness, awareness, interest, desire, book, pre-tour, tour, advocacy) rather than the channel grouping; split the day into two parts, part one on where customers are lost with each agency contributing insights and opportunities, part two on delivery, roadmap and ownership; run part one in two tracks, single day and multi-day, because the behaviours, opportunities and actions differ; and use part two to land an agreed roadmap and actions owned by each team.

**Open.** Awaiting Michelle's confirmation on all four. Evolution (data layer) does not appear in the who-is-who table in `CLAUDE.md`.

---

## 2026-09-08 | Michele's response on the all-agency meeting structure

**Did.** Reviewed Michele's reply to the four points of pushback. She agrees the session should be structured around the customer journey with single-day and multi-day separated, and agrees outputs should be actions, ownership and delivery plans. She asks whether there is additional value in discussing key markets, for example US and UK, and product areas including departure hubs and private tours. Drafted a reply.

**Position taken in the reply, not yet agreed.** Markets go in as a lens applied inside the journey stages where the evidence actually diverges, not as a parallel agenda track. The named divergence points are awareness and interest, where UK customers already know Scotland and the site still addresses them as first-time visitors to the country, trust signals, where ABTA and ATOL carry more weight with a UK audience, and booking window, where the two markets are not on the same timeline. The reason is arithmetic: eight journey stages by two product tracks by two markets is a matrix that cannot be run in a day with four agencies present. Departure hubs and private tours are product and commercial questions, so they sit in part two as short evidence slots against roadmap and ownership, not as journey stages. A time budget for the day to be agreed up front.

**Departure hubs, the argument to carry.** Hub performance today measures where traffic has been sent, not where demand is. A hub with weak numbers may have weak demand or may never have been marketed. That makes it strong evidence for Salience on where commercial value sits, and weak evidence for a decision to back or drop a hub. Structurally the same trap as the late booking pattern in `strategy/2026-09_late-booking-is-a-targeting-artefact.md`. The caveat goes on the slide, not only in the room.

**Private tours, committed to presenting.** Latest results from the interviews now running, framed as early signal rather than findings. Small sample, and no persona behind the segment. `personas.md` records the private-tour pull as a need state layered on the existing four rather than a fifth persona, decided on only 2 private-tour buyers ever interviewed, with that exclusion explicitly marked for revisiting if this research runs.

**Open.**
- `research/2026-Q2-bookers/plan.md` records Private Tours research as briefed and not yet run, with the recruitment answer outstanding. Joe reports interviews currently running. One of the two is out of date. Reconcile before the 23rd.
- `research/2026-Q3-pvt/` held only empty templates. `plan.md` filled in this session. `findings.md` and `SOURCES.md` still templates, and a de-identified synthesis is needed by roughly 19 September to be presentable on the 23rd.
- If markets become a lens across the session, the booker sample skew has to be stated on the page. The sample is US-weighted and multi-day-weighted, so persona evidence describes the market Rabbie's is moving away from better than the one it is moving toward. Assumptions A1 and A12.
- Michele's confirmation still awaited on the four original points as well as these three additions.

---

## 2026-09-09 | Michelle's architecture request, and two committed deliverables

**Did.** Met Michelle at her request. She raised three problems. One, the Ecommerce team
carry too much manual work maintaining products, updating every attribute by hand, at an
unknown cost in hours. Two, PLPs are not showing the right products, because the data
structure is wrong and the manual input is prone to error. Three, localisation is not
routing correctly, so US customers land on UK English pages and see the wrong price and the
wrong content. She asked how to tackle it.

I proposed framing the request as customer value, business value and outcome, so the wider
team buy into an infrastructure change rather than receiving a technical ask. The customer
evidence already exists. The business case is the missing half: Ecommerce hours spent on
manual updates, multiplied by cost per hour, gives the saving to the business. The technical
team should then be asked to bring the solution, which is likely to be the automation we
want anyway. Asking for the outcome keeps the decision with the people who own it.

On customer value, the direct packages, PLP filter data structure, buy box redesign and
landing page initiatives are all treating the customer-facing side of the same underlying
problem. Business value and outcome drafted with Michelle's input.

**Decided.** I own the all-agency workshop format and presentation, coordinating with the
Liberandum and Salience teams to complete the deck. Due 17 September 2026. I also own a
document setting out customer value, business value, business impact and outcome for
Michelle's requested architecture change. Now active work, due 16 September 2026.

**Name correction.** The Rabbie's Marketing Director is Michelle. The entry dated 2026-09-08
spells it "Michele" throughout, and `business.md` carried the same error until today.
Earlier entries in this log stand as written, per the append-only rule. Note that "Michele U"
in `research/2026-Q2-bookers/SOURCES.md` is a research participant, a different person, and
is correct as it stands.

**Open.**
- Michelle has asked Jack at Salience whether the current broken infrastructure carries an
  SEO impact. Answer outstanding.
- Localisation routing is not on the 2026 initiatives backlog. It affects the price and
  content shown to US customers, so it is a revenue issue as well as a UX one. Needs a
  tracker entry or an explicit decision not to add one.
- Initiative 5, Improve PLP data structure, is recorded as blocked on July CRO test
  completion. Michelle's framing points at a broader data and manual-entry cause. Reconcile
  the blocker with the tracker.
- The manual-hours figure is unknown, and without it there is no business case. David, the
  Ecommerce manager, is the obvious owner for producing it.
- Assumption A10, that the current frontend can carry the backlog, rests on nothing and is
  the question underneath this request. The hours and cost work is the first evidence that
  would move it.
- The uncommitted working copy of `CLAUDE.md` has a shorter who-is-who table than the
  version committed at 937baeb. Rob at Liberandum and David, Stuart, Ben and David L at
  Rabbie's are missing from it, and Alex R is shortened to Alex. Restore from git before
  trusting that table. Jack at Salience is in neither version and still needs adding.

---

## 2026-09-09 | Architecture change document drafted

**Did.** Drafted `work/2026-09-09_product-data-architecture-case_v1.md`, the collaboration
document agreed with Michelle. Five sections as agreed: customer value, business value,
outcomes, business impact, success metrics. Michelle's three problems run through each
section as three strands of one case rather than three separate cases, on the argument that
they share a root cause in product data having no single source of truth.

**Decided.** Written for Rabbie's exec and tech leads as the primary audience, with the all
agency meeting on 23 September as a secondary one. The frontend question, A10 and
`strategy/2026-09_frontend-options.md`, is deliberately kept out. Widening the ask into a
patch, strangle or rebuild conversation before the effort comparison exists would spend
credibility on an instinct decision. The document asks for outcomes and leaves the solution
to the technical team.

**Evidence positions taken.** Strand C, localisation routing, is marked on the page as
stated by Michelle and corroborated only indirectly by the copy and trust signal findings.
No participant has been observed landing on the wrong locale. A locale routing accuracy
measure is named as the cheap check that would convert it to instrumented evidence. No
revenue forecast is given, because revenue split by product, margin by line and load factor
are all not held, and sales are not tagged by product.

**Open.**
- The Ecommerce hours figure is still the blocking input. Table in section 2 is built for
  David to fill. Two weeks of time logging named as the method.
- Jack's answer on SEO impact still outstanding and has a placeholder in the document.
- Price and currency display carries consumer protection exposure in both markets. Flagged
  as needing verification, not advised on. Owner unassigned.
- Whether the tour stop data check has ever been completed is still unknown. It gates strand
  B and the compare feature.
- Initiative 5's recorded blocker, July CRO test completion, still contradicts Michelle's
  framing. Not reconciled.

---

## 2026-09-17 | Private tours inversion, and the Appointed Organiser recorded as a role

**Did.** Worked the private tours evidence backwards, from `research/2026-Q3-pvt/findings.md`,
`analysis/sep-2026-rabbies-private-tour-booker-findings.md` and
`analysis/sep-2026-rabbies-customer-insights-data.md`, to establish what Rabbie's should not do to
grow private tour bookings. Held in conversation, not yet written up as a deliverable.

The load-bearing conclusion: private tours is not a demand problem. Nothing in the evidence shows a
shortage of enquiries. What it shows is inconsistent conversion and delivery. Curation quality
varies by whoever picks up the enquiry, accommodation failed in 4 of 4 multi-day bookings, and post
tour feedback reaches roughly half the parties. Driving enquiry volume into that converts a quality
problem into a reputation problem, and in this segment the organiser carries the blame personally,
which is the mechanism that kills referral.

**Decided.** The Appointed Organiser is recorded in `personas.md` as R1, a role, not a fifth
persona. Rationale on the page. The four personas separate on shopping behaviour and this cuts
across all of them: in the sample it appeared on a 12-month planner and on repeat customers alike,
and participants mapped to two personas at once. The existing "Not personas" entry for private tour
buyers has been revisited rather than replaced, with its instinct upheld and its label corrected
from need state to role. No fifth persona created. `CLAUDE.md` rule holds.

**GAP recorded, and it is the one that decides whether any of this is worth doing.** There is no
margin comparison anywhere in the project between a private tour and filled seats on a scheduled
departure. `business.md` holds the general gap, margin by product line, but not this specific
comparison, and the two are not the same question.

Why it matters. Scheduled departures are assumed fixed cost per departure, a guide, a vehicle and a
slot costing roughly the same at four passengers or sixteen, which would make incremental passengers
close to pure margin. Private tours are dedicated cost: one vehicle, one driver, one party, plus
consultant time in the pre-sale phase that is currently unpriced. Every recommendation coming out of
this research adds more of that unpriced time, the planning call, route input into the proposal,
accommodation research with a veto window. CP raised the cost himself in interview, asking who pays
for the driver's hour.

Consequence. Without the comparison, growing private tours could be a margin loss presented as a
growth win, and nobody could tell from the numbers currently held. The same shape as the day tour
versus multi-day mix risk already logged in `business.md`.

What would close it. Contribution per departure for a private tour against contribution per
departure for a scheduled tour at current average load factor, both after vehicle, driver,
accommodation handling and pre-sale consultant time. Owner is Alex, CGO, the same person the
capacity and channel mix gaps are waiting on. Not yet asked.

**Assumptions logged the same day.** Four new entries in `assumptions.md`, all cross-referenced from
the R1 section in `personas.md`.

- **A13** R1 sits behind P4's booking-by-proxy path. Low confidence, an inference layered on weak
  evidence, and the one that touches mobile PDP at rank 1.
- **A14** R1 is not confined to private tours. One documented case, the 13-guest group miss.
- **A15** Group-led demand is understated in the booking data because payments are split. Mechanism
  observed in 2 of 6, size of the distortion unmeasured. Cheap query would settle it.
- **A16** Growing private tour bookings is worth more than filling seats on scheduled departures.
  Rests on nothing. This is the premise underneath the whole question and it has never been examined.
  Falsified by the margin comparison above, which is why the two belong together.

**Open.**
- Margin comparison above. Blocking any recommendation to grow private tour volume.
- Private tour volume and revenue share are still unknown. Sales are not tagged by product, so the
  role R1 describes cannot be sized in either the private or the scheduled catalogue.
- Group payment mechanics split one organiser's decision into several transactions, documented in
  2 of 6. If that is the norm, average PAX per booking cannot size group-led demand at all. Worth
  one query against the booking data to settle. Cheap, and it changes how large this looks.
- R1's P2 overlay is marked assumed in `personas.md` and has deliberately not been logged in
  `assumptions.md`. Nothing currently depends on it, and the file's rule is that assumed attributes
  which work depends on get an entry. Revisit if any initiative starts leaning on it.
- Whether anyone holding the R1 role enquires and does not book is still invisible. Same structural
  gap as Segment B, not closed by this study.

---

## 2026-09-17 | business.md revised against the Spike customer insights pack

**Did.** Checked `analysis/sep-2026-rabbies-customer-insights-data.md`, the Spike Insight pack
presented 08/07/2026, against every gap marker in `business.md`, and revised the file. The question
asked was whether a current dataset belongs in a standing context file. It does not, and that is not
what was done. `business.md` maps the revenue model and its unknowns and points at where numbers
live. What changed is the unknowns, not the file's purpose. Figures were added only where the gap
marker itself became false.

**Gaps closed.** Repeat booking rate, now measured and weak. Channel split, by volume and by value.
Average booking value, at market and channel level. Peak and trough booking months. Party size is
partly closed, mean only.

**Gaps untouched.** Every cost, margin and capacity gap. The Spike pack analyses the customer and
booking database and contains no cost line anywhere. Recorded explicitly in both sections so a
future session does not go looking.

**The statement that was wrong.** `business.md` said channel mix was "entirely unexamined here" and
"nothing in the project speaks to it". That has been false since July. Rewritten. The picture is
also counter-intuitive and worth carrying into the next commercial conversation: OTA is 40% of
bookings and 16.2% of value at an ABV of £123, Agent is 9% of bookings and 20.3% of value at an ABV
of £635, nearly double Direct's £323. The channel Rabbie's has been losing for a decade sells the
largest transactions.

**Marked [assumed], and it is the most useful inference in the revision.** The channel ABV spread is
probably product mix showing through channel. An agent selling a 10 day tour and an OTA selling a day
tour would produce exactly that pattern. If right, it is the strongest evidence the project holds
that multi-day carries the value, which until now was a `[stated]` item with no figure behind it, and
it would reframe the agent decline as a multi-day demand problem. Not checked.

**Correction made to a claim in this repo.** `business.md` recorded the product split gap as
structural because sales are not tagged by product. That is true of GA4 and not of the booking
database, which Spike cuts by tour duration, tour code and named tour. The revenue split by duration
can be requested rather than waited for. Narrowed the claim and named the request.

**Cascade.** `personas.md` P3 said repeat booking rate is not tracked and the persona therefore has
no size. Factually wrong as of July 2026 and corrected in place with a dated note. The correction
weakens P3 rather than strengthening it: 1,346 Loyal customers against 281,902 First Timers, and
roughly half of apparent second bookings are the same holiday split in two. Recorded that nothing
expensive should be built on that persona.

**New section: Reachability.** Email marketing permission on new bookers fell from 96 to 99% on
every cohort to 2020, to 15.4% in 2021, to 8.05% in 2026 to date. Website bookings are 97.8%
marketable over the last three years and every other source is near zero, so the OTA and agent growth
is also growth in unreachable customers. Spike's own caveat is that this may be a tracking convention
change rather than a real consent collapse, and they do not know which. Flagged as verify before
acting, because the two causes lead to completely different work. UK PECR and GDPR exposure flagged,
not advised on, owner unassigned.

**Open.**
- **Lead time contradiction, unresolved and it matters.** Spike reports average lead times of 38.8
  days UK to 85.2 days Australia, 2024 to date. Hard to reconcile with the GA4 distribution in this
  repo showing 69.3% of bookings inside 10 days. Candidate explanation is population: GA4 sees only
  what passes through the site, Spike counts agent and OTA too, and agent bookings peak January to
  March. That would mean direct is late and the business is not. Unchecked. `assumptions.md` A2 rests
  on the lead time picture and the early-window marketing argument rests on A2.
- **A12 now has counter-evidence and has deliberately not been rewritten.** A12 bets on UK growth
  over US recovery. Spike shows UK is the weakest repeat market at 83.6% booking once and the lowest
  ABV at £181 against USA £226 and Canada £310. That does not falsify A12, which is about demand
  direction rather than value, but it means the bet is on the highest volume and lowest value market.
  Per the workspace rule, assumptions are superseded by a new dated entry rather than edited. Needs
  a decision on whether to supersede.
- Three asks now named at the foot of `business.md`, in order of value against effort: revenue and
  ABV split by tour duration from Spike, commission rates by indirect channel from Alex, margin per
  departure private against scheduled from Alex.

---

## 2026-09-18 | Private tours service model mapped

**Did.** Wrote `strategy/2026-09_private-tours-service-model.md`. Eight customer outcomes from the
private tours research, each mapped to the action the customer sees and the backstage change that
has to be true for the action to be possible.

**The finding worth carrying.** Seven of the eight outcomes need no website change at all, and the
eighth needs a price and a link rather than a build. This is a sequence change in how an enquiry is
handled, who is in the room when the trip is designed, and when accommodation gets booked. None of
it can be delivered by the agencies, which determines who has to act and makes this a conversation
with Rabbie's operations rather than with the CRO or design backlog.

**Sequencing taken from the cost line, not from impact.** Four of the eight backstage changes add
consultant or driver hours to the pre-sale phase: qualification, route knowledge in the proposal,
accommodation sourcing moved earlier, and the planning call. Those four are held against A16, the
margin comparison. The other four add no hours and can proceed now: price anchor, group needs record
and its handoff, booking reference, deliverability audit, survey trigger.

**Explicit exclusions recorded on the page** so they do not get relitigated: no private tours page
redesign, no account system, no premium tier, no discounting. Each carries the dissent that rules it
out.

**Open.**
- The survey inconsistency is marked as an inference. The guess is that private bookings sit outside
  the automated post-tour flow. Cheap to confirm and nobody has.
- The accommodation handoff is the highest value item in the memo and the least specified. The AM
  failure was not that the constraint was uncaptured, it was that it did not reach the person
  booking the hotel. Where that record should live has not been established and depends on systems
  nobody here has seen.
- Memo has not been shared with Liberandum or Rabbie's. It is a working synthesis, not a deliverable.

**Same day, v2 of the memo.** Added business impact and measurement columns, reordered from journey
sequence to impact order, and separated do order from impact order because four of the eight items
are gated on A16 and the two orders diverge. Merged the qualification question into the first reply
item as its backstage change. Edited in place rather than superseded, since v1 was written the same
day and never shared, with a version note on the page recording what changed.

**Position taken on impact.** No item is sized in money and the memo says so at the top. Private
tour volume, revenue share and margin are not held, so impact is stated as a mechanism and a
direction only. Two rankings are flagged as uncertain on the page rather than hidden: the indicative
price item could be first and cannot be judged from booker-only evidence, and the planning call is
the most requested item in the research and ranks last on impact because nobody was lost for the
lack of it.

**Cross-check that changed a conclusion.** The private tours implications name the referral argument
as the strongest commercial argument in the study: one organiser converts a party and becomes the
route to the next. The Spike data does not support it as a general case. 89.3% of customers book
once, roughly 3% return the following year, and genuine second bookings are worth 9.8% less than the
first. The two sources measure different populations, so this does not kill the claim, but it does
mean it cannot be asserted while the base rate contradicts it and it cannot be tested either,
because private bookings are not separable in the data. Recorded in the memo as a hypothesis with a
named test rather than as a reason to spend. This is the first case on the account where the July
customer data has changed a conclusion drawn from the qualitative work.

**Open.**
- Item 1, accommodation, is placed in the start-now group on the assumption that moving sourcing
  earlier changes when work happens rather than how much. Not confirmed with whoever books the
  properties. If it does add hours it belongs with the A16 group instead.
- Enquiry to booking rate for private tours is not reported anywhere. Three of the eight measures
  depend on it. It is the missing instrument for this whole programme and nobody has been asked for it.

**Table restructured, same day.** Outcome and front stage split into separate columns at request, so
the memo table now runs outcome, what they see, what has to change behind it, business impact,
measure of success, in impact order. Ranking detail moved out of the cells into notes beneath the
table. Four notes kept: nothing in the measure column is instrumented today, item 6 could be first
and this evidence cannot tell, item 8 is the gap between stated preference and commercial effect,
and item 3 absorbed the qualification question because detection precedes any script.

**Evidence column added.** The memo table now carries the specific observation or quote behind each
of the eight items, with its count, so the ranking can be argued from the page without returning to
the findings document. Participants by initials only. Two entries are deliberately built on a
counter case rather than a supporting one: item 5 uses KA valuing being told he was doing too much,
which proves the same point from the other direction, and item 8 notes that both dissenters were the
two day tour bookers, which sharpens the finding rather than weakening it.

---

## 2026-09-18 | Cascade from the private tours work into six files

**Did.** Checked what was downstream of the private tours synthesis and the business.md revision,
and updated what was genuinely inconsistent rather than what could be tidied.

**`research/2026-Q3-pvt/plan.md`.** The largest gap. The study had run and the plan recorded nothing
about what came back. Closed out against all five questions. Three answered, two not and they cannot
be from this sample. Two of the answers are not the ones the plan anticipated: the custom against
private-version question turned out not to be the decision, and the persona question resolved to a
role, which was not one of the options the plan offered itself. Both hypotheses resolved: the need
state hypothesis superseded, the private-as-fallback hypothesis falsified outright. Also recorded
that accommodation, the highest impact finding, was not predicted anywhere in the plan.

**`initiatives.md`.** Initiative 7 marked delivered as research, with both open questions answered
and a note that what it hands on is a service model rather than website initiatives, which the
tracker has no home for. Recorded explicitly: do not convert them into build rows to make them fit.

**Confidence held at 0.60 rather than raised, and this is the judgement call worth reviewing.** The
study was commissioned to move that number. It closed a different gap from the one the score
measures. Motivation and decision pattern are now well understood; sizing is not, and is blocked
twice, by product separability and by payment splitting. Raising the score on qualitative depth
alone would misrepresent what is known. Sarita or Keating may reasonably disagree.

**Repo `CLAUDE.md`.** It instructed a future session to delete R1. The persona rule now carries an
explicit carve-out for roles, with the test for adding a second one. `decisions.md` and
`failures.md` added to the folder map, since both exist and neither was listed.

**`decisions.md` created.** It did not exist, despite being mandated at workspace level and
referenced by `failures.md`. Two entries: R1 as a role with its reversal condition, and the decision
to hold four of the eight private tour items against A16.

**`failures.md` F8 logged.** The Spike pack sat in `analysis/` for two months while `business.md`
asserted that nothing in the project spoke to channel mix. Root cause recorded as transcription
being treated as complete when the document is accurate, with no step requiring a new source to be
reconciled against the context files it bears on. Cost was low because nothing was delivered on the
false statement, but the near miss is the point: recommending an investigation into something the
client had already commissioned and read is the specific failure mode that damages an advisory
relationship.

**`research/2026-Q3-pvt/findings.md`.** Dated note appended recording the referral cross-check. No
finding, count or dissent edited.

**Open, and needing your decision rather than mine.**
- `assumptions.md` A2 and A12 both now have evidence against them and neither has been touched. A2
  rests on the lead time picture, which the Spike averages contradict. A12 bets on UK growth, and
  Spike shows UK as the weakest repeat market and the lowest ABV. The workspace rule is supersede
  with a new dated entry rather than edit, so both need a written call.
- Whether the reconciliation step in F8 becomes a standing habit. Without it the control is recorded
  and not in place, which `/lint-workspace` will flag at 90 days.

---

## 2026-09-18 | A2 and A12 superseded

**Did.** Both superseded rather than edited, per the workspace rule. A2 and A12 keep their original
text with a pointer line added to the successor. New entries are A17 and A18.

**A17, superseding A2. The lead time divergence resolves in favour of the assumption, not against
it.** Joe's reading, recorded: Rabbie's customers do have a shorter lead time, but that reflects the
type of traffic reaching the site rather than market behaviour. Paid acquisition weighted to the
final weeks selects for people already close to purchase, so the site sees a late deciding
population because that is the population being bought. The qual shows research and consideration
running far longer, specifically on multi-day. Spike's higher averages and the GA4 distribution are
both true of different populations.

Added as corroboration, marked assumed: agent bookings peak January to March at an ABV of £635
against Direct's £323. If the channel ABV spread is product mix showing through channel, the channel
selling multi-day is reaching customers months earlier than direct spend does. Same claim from the
other direction, and it falls if that inference does.

**Confidence deliberately not raised.** A17 stays Medium. The mechanism is better explained and a
contradiction has resolved in its favour, but the size of the recoverable early window is still
unmeasured, which was the original reason for Medium. Raising it on a better explanation alone would
be inflating the rating. Named the cheapest remaining test on the page: GA4 lead time for direct
multi-day bookings alone.

**`business.md` updated to match.** The lead time section no longer carries an unresolved
contradiction. It now states that the GA4 distribution describes Rabbie's traffic mix rather than its
market, and should not be quoted as customer behaviour, because it is a statement about media buying.

**A18, superseding A12. Spike's position taken, with two things held alongside it.** UK is the
weakest repeat market at 83.6% booking once and the lowest ABV at £181 against USA £226, Australia
£271 and Canada £310. Spike's recommendation, that UK retention is the single biggest lever because
the largest and weakest market moves the most absolute customers, is recorded as adopted.

**Two challenges recorded on the page rather than smoothed over.** First, the same Spike deck also
recommends leaning into Canada and Australia on higher ABV and CLTV, and does not reconcile the two.
Most absolute customers is a volume argument, and at £181 against £310 more UK customers can be worth
less than fewer Canadian ones. Nobody has done that arithmetic. Second, the retention half of the
bet is blocked by reachability, not by strategy: email permission on new bookers is 8.05% in 2026,
and a retention programme cannot run against a base that cannot be emailed.

**Confidence split rather than given as one figure.** Medium on the demand direction, unchanged. Low
on this being the best use of the effort, which is the new question and the part actually in doubt.

**Open.**
- The CLTV comparison that would settle A18. UK volume growth at £181 with a 16.4% repeat rate
  against equivalent effort on Canada or Australia. Named as the falsification condition and not
  run.
- Reachability cause still unknown, and it gates A18. Tracking convention change or real consent
  collapse. Cheap to establish, nobody asked.

---

## 2026-09-21 | Single customer outcome statement drafted for the all-stakeholder workshop

**Purpose.** A framing statement for the customer journey section of the all-stakeholder workshop,
and the activities under it. Asked for as one statement, not a set.

**The statement.** "I want the time I have in this place to be worth it, run by someone who knows it
better than I do, and I need to be sure of that before I pay."

**Derivation.** Read across the "What they are trying to do" sections of P1 to P4 and R1 in
`personas.md`, against the strong findings in `research/2026-Q2-bookers/findings.md`. Three clauses
survived all five.

- Time, not price, is the named constraint. P2 rejects seven to eight day tours as over-commitment,
  P4 has a single free day, R1 had 5 of 6 not treating price as a barrier.
- The handover of planning, driving and risk is the product. Post-tour attribution of roughly 90% of
  experience quality to the guide. R1 organisers buying delegated expertise and blame reduction.
- Certainty before payment is where the money is lost. The 92% interest and desire drop-off is the
  same fact stated from the other side.

**Why it links to the business outcome.** Rabbie's is paid for carrying planning work and risk.
Delivery of that is strong, proof of it before payment is not. Frames the workshop question as which
journey step supplies enough certainty to commit, which each function can answer for its own step.

**Qualifiers carried with it.** Two tracks, not one: multi-day weights the pre-payment certainty
clause and puts accommodation inside the handover, day tours weight the worth-the-time clause and
must prove it on mobile in seconds. Where R1 is present, a fourth clause applies, that it will not be
the organiser's fault.

**Evidence boundary stated on the slide.** First two clauses directly observed across Segments A, C
and D. Third is inferred from drop-off location, not from any participant describing leaving.
Segment B still not recruited.

**Not logged as a decision.** It is a framing device for a workshop, not a choice with a reversal
condition. If it is adopted as the shared customer frame across the three agencies, that becomes a
`decisions.md` entry at that point.

---

## 2026-09-21 | Initiatives mapped to the eight journey phases for the 23 September workshop

**Did.** Built `work/2026-09-21_workshop-initiatives-by-journey-phase_v1.md`. All 17 parent
initiatives and their sub-tasks from `initiatives.md`, dealt into the eight phase structure agreed
with Michele on 08/09/2026: pre-awareness, awareness, interest, desire, book, pre-tour, tour,
advocacy. Each carries focus, status, product track, a proposed success measure, and the tracker's
own phase tag where it disagrees.

**The headline.** The entire backlog sits in two of the eight phases. The tracker's phase column
carries only Interest and Desire. Four phases have nothing on the backlog: pre-awareness, awareness,
pre-tour and tour. Book and advocacy hold sub-tasks of larger parents only. Defensible for a UX and
CRO engagement pointed at the 92% interest and desire drop-off, and useful on the day because the
four empty phases belong to the other agencies in the room.

**Three gaps surfaced by the mapping.**
- No initiative on the tracker carries a measure of success. The workbook has `CRO test` and
  `CRO test focus` and no success measure column. Every measure in the draft is proposed by Sunny
  Lemons, unagreed, with real sourced baselines and blank targets.
- Two documented failures sit in pre-tour with no initiative behind them: months of silence between
  booking and accommodation confirmation, and unclear end-of-tour drop-off when a tour ends in a
  different city. There is a design document and no tracker row.
- The private tours service model lands in pre-tour and enquiry, where the tracker has no home for
  it. Seven of its eight outcomes need no website change. Recorded again that these should not be
  converted into build rows to make them fit.

**Phase assignment is by function, not by the tracker.** Divergences are shown rather than
corrected silently. The largest is navigation redesign, tagged Desire in the tracker and placed in
Interest here. Owned reviews, referral, post-tour email and account are tagged Return in the tracker
and split across Desire, Book and Advocacy here.

**Two items flagged for reconciliation before the 23rd.** Research the european bookers is recorded
as In Design running to mid-September, and the tracker sync date is 05/09, so the status needs
confirming. The 8.05% email permission rate on 2026 bookers gates the retention half of the UK market
bet, A18, and nobody has established whether it is a tracking convention change or a real consent
collapse.

**Open.** Success measures need agreeing in the room, not drafted for it. Nine efforts are still TBC.
Draft is in `work/` and has not been delivered.

---

## 2026-09-21 | Private tours research summarised for the 23 September workshop

**Did.** Built `work/2026-09-21_workshop-private-tours-summary_v1.md` from
`research/2026-Q3-pvt/findings.md` and `strategy/2026-09_private-tours-service-model.md`. Written for
the part two evidence slot rather than as a journey stage, which is the position taken in the 08/09
reply to Michele. Cross-referenced from the journey phase draft.

**Structure.** Headline, study boundary on the slide rather than in speaker notes, what changed in
our thinking, findings grouped by evidence strength, actions in do order with owner and measure, what
is deliberately not recommended, and two asks from the room.

**The framing carried into the room.** Private tour customers are buying someone to take
responsibility for a group, not a better tour. Seven of the eight outcomes need no website change, so
the actions land on Rabbie's operations rather than on any agency in the room. Said plainly in the
draft rather than softened.

**Three things held deliberately.**
- The referral argument stays out as a reason to spend. Recorded as a hypothesis with the named test,
  whether private party organisers rebook at a materially different rate from the 10.7% base.
- The four "not recommending" items are on the page, because a page redesign, an account system, a
  premium tier and discounting are each the obvious thing to reach for and each is contradicted by
  the evidence.
- Sample boundary stated three ways: all six converted, so price abandonment is structurally
  invisible; 5 of 6 North American; no mobile observation in this round.

**Two asks put to the room.** The enquiry to booking rate for private tours, which is not reported
anywhere and which three of the eight actions depend on. The margin comparison against filled
scheduled seats, A16, which gates three actions and currently rests on nothing.

**Open.** Neither draft has been formatted for delivery. If a deck is wanted for the 23rd it needs
building as `.pptx` via `pptxgenjs` with speaker notes on every slide, and the two drafts are the
content source. Nothing in `work/` has been agreed with Liberandum or Rabbie's.

---

## 2026-09-22 | How Might We statements drafted for all eight journey stages

**Did.** Built `work/2026-09-22_workshop-hmw-statements_v1.md`. One framing HMW per stage for the
slide, three to four sharper ones underneath for the activity, each with the track it belongs to and
the evidence behind it.

**Source of the questions.** Pre-awareness, awareness, interest and desire, and book came from Joe as
participant quotes. Pre-tour, tour and advocacy had none, so the customer question for those three is
drafted from the research and marked on the page as drafted rather than quoted. Real candidate quotes
are named for pre-tour and advocacy, both available in the research and both better than a drafted
question. Tour has only the single completed-tour interview behind it, so any quote there carries a
single-voice caveat.

**Interest and desire separated.** The supplied set merged them. Separated in the draft, because
interest asks whether a trip that fits exists and desire asks whether this specific tour can be
trusted, and the two fail for different reasons. Noted that they can merge on the slide if the day is
short, but the activity should run twice.

**Track assignment added to every stage, and one finding came out of doing it.** Pre-awareness is
multi-day only, because the trip has to exist before a day tour can fill it. Pre-tour is almost
entirely multi-day for the same reason in reverse. Running either in both tracks wastes half the
room.

**Two blockers carried onto the stage slides rather than left as ideas.** Email permission at 8.05%
gates the whole advocacy stage and the cause is undiagnosed. The advocacy persona is the weakest in
the set at 65% and Spike sizes it at 1,346 loyal against 281,902 first timers, so everything proposed
there stays cheap.

**Correction.** The previous session's reply said this file had been saved. It had not. Written this
session, with the three additional stages included.

**Open.** Three of the eight stage questions are drafted rather than quoted and should be replaced
with real participant quotes before the deck is built. Nothing in `work/` has been agreed with
Liberandum or Rabbie's.

---

## 2026-09-24 | Rabbie's management 2027 focus recorded

**Received.** Via Joe, the management team's stated 2027 focus: "Scaling Scotland, growing Multi Day,
and understanding our target markets and the opportunity within them so we can leverage this.
Alongside supporting non Scotland growth for the future." This is a Rabbie's decision, not an
engagement decision, so it is logged here rather than in `decisions.md`.

**Read against the file.** Growing multi-day matches the strongest evidence held (two-track model,
product mix, GI-02). Four open points: "scaling Scotland" is undefined and, if it means volume,
leans on day tours and runs into the unknown load factor; understanding target markets meets the
unresolved UK volume against Canada and Australia value tension in A18; non-Scotland has no measure
attached and is structurally disadvantaged by listing pages (GI-03) and by the brand being read as
Scotland only (private tours research); the contracted site-wide 1% conversion measure does not
track any of the four clauses. The Spike Scotland 33.7% figure is customer home region, not tour
destination, and must not be quoted as a destination share.

**Open.** Revenue by destination and duration is not held. The engagement ends 05/01/2027, so this
focus is the natural frame for the renewal proposal.

---

## 2026-09-24 | State of the Nation deck reconciled against the context files

**Source.** `work/sep2026_state-of-the-nation_rabbies_performance.md`, transcription of the deck
Rabbie's presented at the all agency session. Trading data YTD P1 to P8. It sits in `work/` but it is
a client source rather than our draft, so it arguably belongs in `analysis/`. Not moved.

**Updated.**
- `business.md`: revision note added. Revenue by line against budget, with derived sizes (Single
  Day about £10.3m, Multi Day about £9.6m). Private tours sized at £3.9m. Fixed cost base moved from
  assumed to stated. Departure hub performance. B2B as fastest grower. Direct CVR baseline 1.68%.
  US against UK conversion. Management's stated beliefs and the 2027 focus. August paid media
  figures marked compromised by the tracking bug.
- `assumptions.md`: A19 supersedes A18, UK bet now low confidence. A20 supersedes A16, private tours
  margin question raised in stakes.
- `failures.md`: F9, platform figures recorded as observed without a source system.

**Correction to the earlier entry today.** That entry said revenue by destination and duration is
not held. Revenue by product line is now held against budget and hub performance is known. Revenue
by destination is still not held. Hub is departure point, not destination.

**Not updated, needs a decision.**
- `strategy/2026-09_late-booking-is-a-targeting-artefact.md` and
  `strategy/2026-09_uk-versus-us-market-bet.md` both rest partly on the compromised figures and need
  superseding memos. The UK memo also faces the client's own contrary position.
- Both product data architecture case drafts in `work/` quote the same figures. Fix in the next
  version.
- `initiatives.md` and the tracker: RICE rank 2, UK local content, rests on A19.
- `engagement.md`: whether the 1% target is relative or absolute is unresolved in the SOW. With the
  baseline at 1.68%, this needs settling before the renewal conversation.
- The deck lists "Migrated the site to Nuxt" as delivered this year. `strategy/2026-09_frontend-options.md`
  and A10 do not mention it. If the rebuild has already happened, both may be framed against a
  frontend that no longer exists.
- Management attributes the Direct miss to a later-booking market. That contradicts A17 directly.
  The GA4 lead time test on direct multi-day bookings is now the most useful single piece of
  analysis the account could run.

---

## 2026-09-24 | Workshop opportunities collated against the backlog, v2

**Did.** Built `work/2026-09-24_growth-initiatives-from-workshop_v2.md`, superseding v1 of the same
date. All 68 post-its, 314 votes, assigned once each to twelve opportunities. Each item classified
as covered, extend, task, small project, new initiative or decision, and labelled UX, SEO, Paid
media, Social & Content, Tech or Ops.

**Product data foundation added as OP-01**, per the position established outside the workshop. 110
of 314 votes sit on problems it fixes in whole or part. Recommended as a new parent initiative
absorbing initiative 5, not a sub-task of it.

**Corrections to v1.** Removed "roughly 1.9 FTE": ecommerce team size is not held. Guide 90% claim
corrected to single voice. Removed the claim that most of the 92% drop-off sits on listing pages.

**Discrepancies found.** Ecommerce time on product updates is 65% on the wall and 50 to 60% in the
working estimate. Neither is time logged. The State of the Nation deck lists abandoned basket as
delivered while the wall says it does not exist.

**Open.** Nothing in `work/` has been agreed with Liberandum or Rabbie's. Nine decisions have no
owner. The product data architecture case v2 still records the ecommerce hours as not held and
should pick up the stated estimate in its next version.

---

## 2026-09-24 | Workshop opportunities v3, scored and ranked

**Did.** Built `work/2026-09-24_growth-initiatives-from-workshop_v3.md`, superseding v2. All 52 items
scored on business value (1 to 5), customer value (1 to 5) and effort (XS to XL, points 1, 2, 3, 5,
8). Priority score is value divided by effort. Ranked list added. Evidence shown per item but not
scored. Items at M or larger resting on workshop votes or a single voice are marked validate first.

**The finding worth holding.** The two new initiatives, product data pipeline and multi-tour basket,
rank 50th and 51st, because value over effort always penalises platform work. The document says so
and names four overrides: gates, enablers, risk and lead time. Accommodation content on multi-day
tour pages ranks 4th here against an unranked 0.450 sub-task score on the tracker RICE.

**Open.** All scores are Sunny Lemons estimates, not developer estimates, and have not been
reviewed with Liberandum or Rabbie's.

---

## 2026-09-24 | 2027 delivery plan drafted

**Did.** Built `work/2026-09-24_2027-delivery-plan_v1.md` from the v3 workshop ranking, the tracker
and the State of the Nation deck. Four phases: measure and decide (Oct 2026), ready for the January
multi-day peak (Oct to Dec 2026), build (Jan to Jun 2027), scale (Jul to Dec 2027). Action lists for
Rabbie's (leadership, ecommerce, tech, marketing and CRM, operations, finance, paid media),
Liberandum, Sunny Lemons, Salience and Evolution, with dates, dependencies and measures.

**Position taken.** "Increase seats" defined as seats sold per existing departure, not more
departures, consistent with management's stated fixed cost base. Profit is not measurable yet:
contribution per departure, load factor and commission rates are the first ask, due 31/10/2026.

**Open.** Paid media owner not recorded in the project. Evolution's scope unconfirmed. Sunny Lemons
actions after 05/01/2027 depend on renewal. Nothing agreed with Liberandum or Rabbie's.

---

## 2026-09-24 | Intended outcomes added to workshop opportunities v3

**Did.** Added an intended outcome to all 12 opportunities and all 52 items in
`work/2026-09-24_growth-initiatives-from-workshop_v3.md`, as a new column in each item table. Edited
v3 in place at Joe's request, with an amendment note at the top. Scores, ranks, types and labels are
unchanged.

**Open.** Outcomes are Sunny Lemons proposals and need agreeing alongside the measures (OP-12.1).
The 2027 delivery plan does not yet carry these outcomes.

---

## 2026-09-24 | Workshop opportunities v4, led by the existing initiatives

**Did.** Built `work/2026-09-24_growth-initiatives-from-workshop_v4.md`, superseding v3. Part 1
tests the 17 tracker initiatives against the workshop: votes landing on each, what the workshop
adds, and a movement per initiative or part (forward, held, back, re-scoped, split, delivered) with
a phase. Part 2 is v3's opportunity detail, scores and ranking, unchanged, minus the two sections
Part 1 replaces.

**Finding.** 173 of 314 votes (55%, 34 of 68 post-its) land on problems an existing initiative
already tackles, 66 of them on Direct Packages 2.0 and its sub-tasks. No workshop problem argues
against an existing initiative. The other 141 votes sit in phases the backlog never covered: booking
to travel, multi-tour booking, product data and operations, markets. Eleven items forward, five
back (8 overall templates, 10 account build and invite to tour, 11 customer support, 13 compare).

**Caveat recorded on the page.** The backlog was prepared as workshop input, so the overlap is
corroboration from people who knew the plan, not independent validation. The post-it to initiative
mapping is a Sunny Lemons judgement, one initiative per note.

**Open.** `initiatives.md` and the tracker workbook are not updated. The movements are proposals
until agreed. Initiative 14 needs re-scoring on the market-by-market framing.

---

## 2026-09-24 | 2027 delivery plan v2, by team and bucket

**Did.** Built `work/2026-09-24_2027-delivery-plan_v2.md`, superseding v1. 72 actions, each with one
lead team (CRO, SEO, Paid media, UX, Content & Social, Tech, Operations, or Rabbie's leadership for
decisions) and one bucket: 22 quick wins, 24 small projects, 11 larger initiatives, 15 decisions.
Sequence aligned to the initiative movements in workshop v4. Team views generated from one master
list so counts and sections cannot drift.

**Positions taken.** Decisions added as a fourth bucket because they have no delivery team and would
otherwise be lost. Ecommerce and Finance sit under Operations, following the workshop's grouping.
Quick win means no dependency, not merely small: accommodation content on multi-day tour pages is a
small project because it waits on the accommodation scenario decision.

**Open.** Paid media owner and Evolution scope still unconfirmed. Nothing agreed with Liberandum or
Rabbie's.

---

## 2026-09-24 | Delivery plan v3: Salience owns paid media, actions reassessed on 2027 impact

**Fact recorded.** Salience owns paid media as well as SEO. `CLAUDE.md` who-is-who updated.

**Did.** Built `work/2026-09-24_2027-delivery-plan_v3.md`, superseding v2. Every quick win, small
project and larger initiative scored on 2027 impact: (seats and revenue 0 to 3 + margin 0 to 3 +
focus fit 0 to 2) × evidence (1.0, 0.75, 0.5) × lands (by 31/03/2027 1.0, by 30/06/2027 0.6, H2
2027 0.3). Enablers listed with what they unlock rather than scored. Decisions treated as gates.

**Top of the list.** QW-15 cross-sell 7.00, LI-02 Direct Packages 7.00, SP-04 accommodation content
6.00, SP-10 paid split 5.25, SP-24 merchandising under-filled departures 5.25. Four of the top five
wait on a Phase 0 gate.

**Changes made.** Owned reviews forward to 31/03/2027. Persist dates, rebook segmentation and
CAD/AUD currency deferred to Phase 3. Buy Box, day-before SMS and deposits made validate-first or
measured from launch. Multi-tour basket scope forward to 31/03/2027. Product data foundation to be
argued on cost, not 2027 revenue, because it lands late.

**Open.** Scores are Sunny Lemons judgement, not forecasts. Nothing agreed with Liberandum, Salience
or Rabbie's.

---

## 2026-09-24 | Delivery plan v4: rescored on Rabbie's stated focus and objective, resequenced

**Clarified by Joe.** Three separate statements from Rabbie's: the 2026 focus (volume from secured
inventory against a fixed cost base), the 2027 focus, and the objective for this work (biggest
impact, cost-effectively, minimal complexity, rest of 2026 and into 2027). The retention opportunity
is the next tour sold before arrival. Navigation and IA is complete: more people reach listing
pages, and listing pages fail to move them on to tour pages. Tech capacity reduces in 2027. The
product data foundation should start now.

**Did.** Built `work/2026-09-24_2027-delivery-plan_v4.md`, superseding v3. Scoring now has impact
(seats, margin, focus, evidence, timing with 2026 delivery credited) and priority (impact divided by
effort plus complexity). Sequencing rules set out where the order departs from priority: mandatory,
gates, Tech capacity window, dependencies, 2026 volume first. A Tech lane orders Rabbie's developer
work by window. Added LI-12 listing page rebuild, DC-16 consent basis for pre-arrival offers, DC-17
Tech capacity. LI-03 removed as delivered. `initiatives.md` carries a dated status note on
initiative 1.

**Positions taken.** The product data foundation starts October and completes by 31/03/2027, ahead
of its priority score, because of the capacity window and the LI-12 dependency. It is a Tech build
but needs the UX attribute definition and Ecommerce input by 31/10/2026. The multi-tour basket and
the account build become 2028 candidates unless capacity is confirmed; confirmation and pre-arrival
cross-sell carries the 2027 value.

**Open.** The Tech capacity date, the consent position for pre-arrival offers, and the listing to
tour page figure before and after the navigation launch. Workshop v4 still shows initiative 1 as in
QA and predates this rescoring.

---

## 2026-09-24 | Delivery plan v5: consent confirmed, capacity unknown, funnel figures in

**From Joe.** Booked customers can be emailed with offers (DC-16 resolved). Tech capacity reduction
date unknown (DC-17 open). Funnel losses: tour page to checkout 82%, guest details to payment 53%,
listing page to tour page 52%. Joe's reading of the 53%: accumulated doubt at the commitment point.

**Did.** Built `work/2026-09-24_2027-delivery-plan_v5.md`, superseding v4. Tour page actions rescored
up, since the tour page, not the listing page, is the biggest leak. Added QW-23 payment tracking
check, SP-25 cancellation terms, inclusions and full price shown early, SP-15 reframed as the
commitment-point test by 31/01/2027. Buy Box split into two parts, with its usability study moved to
Q4 2026. Tech lane ordered so the bottom of each window is cut first. `business.md` updated with the
funnel figures and the consent position. `assumptions.md` A21 added.

**Position taken.** The listing page rebuild stays, carried by the product data foundation, but is
no longer described as the main constraint. The earlier framing that listing pages are the problem
was stronger than the figures support.

**Open.** Funnel split by product and date range. Payment step tracking. Cancellation terms. Tech
capacity. Workshop v4 predates v4 and v5 of the plan.

---

## 2026-09-24 | Correction: the 82% tour page loss is per person and is site exit

**Correction.** In the v5 plan and in chat I said part of the 82% tour page to checkout loss was
comparison shopping between tours, and that it should be measured per person. Joe confirmed it is
already measured per person, and those people leave the site. The claim came from applying the 52%
multi-day browsing figure to a metric without checking how the metric was built. Corrected in
`work/2026-09-24_2027-delivery-plan_v5.md` with a correction note. No score or sequence changed.

**What follows.** The tour page is the largest point at which acquired visitors are lost. They never
reach a basket, so abandoned basket flows cannot reach them. Retargeting and the tour page itself are
the only levers. Where they go is unknown, which is the non-booker research gap.

---

## 2026-09-24 | Workshop opportunities v5, aligned to delivery plan v5

**Did.** Built `work/2026-09-24_growth-initiatives-from-workshop_v5.md`, superseding v4. Part 1
rewritten against plan v5: initiative 1 delivered, funnel figures added, each initiative's parts
mapped to plan v5 action IDs and dates, 13 items forward and 6 back, evolved sequence on plan v5's
windows. Part 2: v3 scoring and ranked list withdrawn so plan v5 is the only scoring in circulation;
each workshop item's last column now gives its plan v5 action and date (52 of 52 mapped; OP-11.2 is
held behind DC-13 and not scheduled). Consent and permission notes updated.

**Found and fixed in plan v5.** OP-03.3 (accommodation on tour cards) and OP-04.4 (destination
detail and multi-day map) had dropped out when v4 re-scoped LI-01. Now LI-12 and new SP-26. Also
aligned the Direct Packages booking flow timing: rollout by 31/03/2027, booking flow changes by
30/06/2027. Correction note added to plan v5. Plan now 77 actions.

**Added to the "confirms" argument.** The 53% guest details to payment figure corroborates the 60%
personal details loss that initiative 2 was originally prioritised on.

---

## 2026-09-25 | Paid media post-booking actions added to plan v5 and workshop v5

**Gap raised by Joe.** No paid media action targeted people after booking. Cause: the workshop
post-it "Retargeting Meta email web (limited to none)" mapped to OP-09.2, which became an audit only
(QW-06) with no follow-on action.

**Did.** Amended `work/2026-09-24_2027-delivery-plan_v5.md` and
`work/2026-09-24_growth-initiatives-from-workshop_v5.md`, with amendment notes. Added QW-24, which
excludes recent bookers from acquisition and retargeting for the tour they booked (priority 2.25,
second of the quick wins). Added SP-27, a post-booking paid campaign for second-tour offers before
travel, by lead time, on the known tour pairs, with a holdout (impact 4.50, eleventh overall). Added
DC-18, the lawful basis for paid targeting of booked customers. Plan now 80 actions.

**Positions taken.** SP-27 is run against a holdout, because 37 to 41% of second tours are booked
the same day and paid could buy bookings that email and the confirmation page would win anyway.
Confirmed email consent is not treated as covering pixel audiences or customer list matching.
Flagged, not advised on.

---

## 2026-09-25 | Delivery plan v6 and workshop opportunities v6: six gaps added

**Did.** Built `work/2026-09-25_2027-delivery-plan_v6.md` (86 actions) and
`work/2026-09-25_growth-initiatives-from-workshop_v6.md`, superseding the v5 of each. Added:
QW-25 guides and vans offer the next tour during the trip (priority 1.75), QW-26 phone and chat on
multi-day tour pages and guest details (1.50), SP-28 retargeting tour page leavers (0.94), SP-29
email me this tour, taken out of LI-07 (0.72), SP-30 abandoned basket gaps, guest details first
(1.75), and SP-24 extended to offers and paid for under-filled departures with a holdout (1.05, down
from 1.31 because it now involves three teams). New DC-19, lawful basis for abandoned basket emails.
Initiative 11 split in workshop v6: phone and chat forward, central help page back.

**Pattern worth holding.** Three of the gaps found over two days (paid post-booking, retargeting,
abandoned basket) came from audit actions with no follow-on. Any future audit action should be
paired with the action that closes what it finds.

**Also fixed in plan v5.** The lever 1 table had not listed SP-27 and QW-24 after the 25/09
amendment. Corrected in place, covered by the existing amendment note.
