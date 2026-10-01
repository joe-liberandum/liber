# Assumptions: Rabbie's

The beliefs this engagement rests on that are not established facts. Facts go in `CLAUDE.md`,
decisions go in `decisions.md`, and the load-bearing beliefs in between go here.

This is the file a strategic session should attack. Most circular strategy conversations happen
because the thing actually in question was never written down, so it never gets challenged
directly.

Review when new evidence arrives, not on a schedule. Move an assumption to `CLAUDE.md` when it
becomes established, and log the change as a decision when a falsified assumption changes course.

Format:

## A<n> Short statement of the belief

**Rests on.** What makes this credible right now. Evidence, or an honest "nothing yet, this is
inherited from the brief".

**Falsified by.** What observation would show this is wrong. Must be something you could actually
see.

**Depends on it.** What work or recommendation collapses if this turns out false.

**Confidence.** High, medium, or low. Reviewed <date>.

---

## A1 The four personas describe the market, not just the people who bought

**Rests on.** Four research waves: Segment A bookers (26 sessions held), Segment C competitor
bookers (6, no source files currently held), Segment D active planners with no Rabbie's knowledge
(6), and one post-tour interview. Segment D
strengthened the Meticulous Planner and Pragmatic Day-Tripper without contradicting the set. Segment
C covers why a competitor won. Nothing so far has produced a motivation the four do not cover.

**Falsified by.** Segment B, site and cart abandoners, surfacing a dominant motivation none of the
four hold. That wave is scoped but not yet recruited, and it is the one wave that observes the
moment of leaving rather than reconstructing it. Late availability bookers and group and private
hire are also logged as segments with no persona behind them, so either could break it.

**Depends on it.** Everything. All persona-targeted initiatives, all reach and impact scoring in
the RICE model, and the shared customer frame across Sunny Lemons, Liberandum and Salience.

**Confidence.** Medium, and better than it was. The competitor and active-planner waves close most
of the non-booker gap; what remains is specifically the abandonment moment. Reviewed 07/09/2026.

---

## A2 Late booking is an artefact of late targeting, not late deciding

**Superseded by A17, 18/09/2026.** Original text below, unaltered.

**Rests on.** Booker interviews consistently reporting consideration windows of months that appear
in GA4 as first-session bookings. Australia showing an earlier booking pattern under different
spend timing. Safari's seven-day cookie cap and cross-device identity loss both compress observed
windows in the same direction.

**Falsified by.** Spend moved into an earlier window producing no incremental bookings over a full
season. Or attribution work showing the long consideration windows customers report do not
correspond to trackable earlier site visits, meaning the demand is not reachable earlier even if it
exists.

**Depends on it.** The whole Scaling Interest recommendation and the marketing timing argument in
the August deck. If false, the current spend timing is correct and the drop-off problem is entirely
on-site.

**Confidence.** Medium. The mechanism is well argued. The size of the recoverable early window is
not established. Reviewed 07/09/2026.

---

## A3 The 92% interest and desire drop-off is addressable, not category-normal

**Rests on.** Nothing external. This is inherited from the brief and has never been benchmarked
against comparable operators or OTAs.

**Falsified by.** Competitor or category benchmarking showing similar browse-to-book ratios for
small group tour operators. A high drop-off rate that is normal for a considered, high-value,
date-dependent purchase would reframe the entire engagement from fixing a leak to competing for a
share of a naturally low conversion pool.

**Depends on it.** The framing of every deck delivered so far. The 1% conversion target implicitly
assumes headroom exists.

**Confidence.** Low. This is the assumption most often repeated and least often examined.
Reviewed 07/09/2026.

---

## A4 Mobile paid social traffic is qualified, so the mobile PDP is a layout problem

**Rests on.** Paid social drives high mobile volume with low booking conversion, and the mobile PDP
buries reviews, group size and map below the fold. The inference from those two facts to "layout is
the cause" has not been tested.

**Falsified by.** Traffic quality analysis showing paid social sessions have materially worse
intent signals than other mobile sources, for example bounce within seconds, no scroll depth, no
tour-page depth. Or the mobile PDP reorder shipping with no conversion movement.

**Depends on it.** Mobile PDP layout optimisation, which is RICE rank 1 on the tracker at reach 5,
impact 3, 4 days effort. If the traffic is poorly targeted, the highest-ranked item on the backlog
returns nothing and the problem belongs to media buying.

**Confidence.** Medium. Cheap to check before building. Reviewed 07/09/2026.

---

## A5 Moving qualification upstream reduces booking-flow abandonment

**Rests on.** 60% drop at the accommodation step and 60% at personal details in the multi-day flow.
Three participants entered checkout specifically to find accommodation information, which supports
the claim that research-intent users are entering the funnel early. It does not establish that the
60% are those users.

**Falsified by.** User testing showing the accommodation-step drop is driven by price or genuine
disqualification rather than missing information. Or PDP accommodation surfacing shipping with the
booking-flow drop unchanged.

**Depends on it.** Direct Packages 2.0 in full, plus the surface-accommodation and guide-module
sub-tasks. Also the general principle in `CLAUDE.md` that qualification belongs on the PDP.

**Confidence.** Medium to high. The tracker already requires user testing before design to confirm
root cause, which is the right sequencing. Reviewed 07/09/2026.

---

## A6 Guide visibility before booking drives conversion, not just loyalty

**Rests on.** Guide quality is the primary driver of rebooking, and one day-tour customer
attributed roughly 90% of experience quality to the guide. Almost all of that evidence is post-tour.

One pre-booking signal exists, identified 07/09/2026 and weaker than it first looks: a repeat
customer planning a trip named Rabbie's current social video content, shot by someone riding along
on tours, as the strongest thing they do to pull her toward a tour. That is experience content
working before booking. It is not the guide, and she is a returner rather than a first-timer, so it
does not close the inferential gap. It does show the gap is testable with content that already
exists.

**Falsified by.** The PDP guide module shipping with no measurable lift in desire-to-book
conversion. Or pre-booking research showing customers do not weigh named guides when choosing
between operators, because they cannot yet evaluate a person they have not met.

**Depends on it.** The guide module on PDP. More broadly, the claim in `CLAUDE.md` that
driver-guides are one of only two genuine differentiators. If guides only matter after the fact,
they are a retention asset, not an acquisition one, and the differentiator argument weakens.

**Confidence.** Medium. This is a real inferential leap from loyalty evidence to acquisition
evidence and is not currently labelled as one in the deliverables. Reviewed 07/09/2026.

---

## A7 Owned, attributed reviews will fix the trust break

**Rests on.** Two Segment D participants independently lost confidence at the review section, one
moving to a firm no almost entirely on that basis. Rated 95% confidence in Segment D research, and
the highest-confidence item on the tracker.

**Falsified by.** Owned reviews shipping at volume with no movement in PDP-to-booking conversion.
The evidence establishes that the current reviews section breaks trust. It does not establish that
owned reviews are the fix rather than, for example, review volume, recency, or photo attribution.

**Depends on it.** Owned reviews, RICE rank 4, 15 days. Note the effort figure is a Sunny Lemons
placeholder for "Large", not a dev estimate, so both the rank and the case rest on soft numbers.

**Confidence.** High on the problem, medium on the solution. Worth separating those two in any
deck that cites the 95%. Reviewed 07/09/2026.

---

## A8 Deposits will recover hesitant bookers

**Rests on.** One participant describing a reserve-now-pay-later feature seen elsewhere as
excellent. That is the entire evidence base.

**Falsified by.** Abandoner research showing hesitation is driven by date certainty, trip planning
sequence, or price level rather than payment timing. Or deposits shipping with no change in
multi-day conversion.

**Depends on it.** The Deposits initiative, currently being scoped separately, plus the deposit
messaging changes that are the stated opening for the wider Buy Box work. If deposits are the wrong
lever, the Buy Box changes lose their trigger.

**Confidence.** Low. The tracker already flags this as an open research question with no persona
assigned. Treat it as a bet, not a finding, in any client conversation. Reviewed 07/09/2026.

---

## A9 The 3 to 4 day duration gap is real unmet demand

**Rests on.** Repeated requests across the Purposeful Adventurer persona and two Segment D
participants, against 7 to 8 day tours perceived as too long. Flagged as the highest long-term
revenue opportunity in prior research.

**Falsified by.** Stated preference not converting. Pilot tours at that length underperforming on
load factor or margin. Operationally, a 3 to 4 day tour may not be viable at Rabbie's cost base,
which would falsify the recommendation without falsifying the demand.

**Depends on it.** The product catalogue recommendation. Nothing on the current initiative backlog
depends on it, which is worth noticing: the largest claimed revenue opportunity has no owner and no
initiative.

**Confidence.** Medium on the demand. Low on viability, which has never been assessed.
Reviewed 07/09/2026.

---

## A10 The current frontend can carry the initiative backlog without a rebuild

**Rests on.** Nothing. The comparison of initiative effort against current versus rebuilt frontend
has been identified as necessary and has not been done.

**Falsified by.** Effort estimates for IA restructure, landing page templates and the design system
coming back materially higher against the current frontend than a rebuild would cost to amortise.
The nine TBC efforts on the tracker are where this would first show.

**Depends on it.** Every effort figure in the RICE model, and therefore every rank. Also the
implicit sequencing of the whole 2026 roadmap. The strangler-pattern option exists precisely
because this assumption is unresolved.

**Confidence.** Low. This is a known gap being carried rather than closed. Reviewed 07/09/2026.

---

## A11 The initiative backlog adds up to the 1% conversion target

**Rests on.** Nothing. No initiative on the tracker carries a forecast conversion contribution, and
no one has modelled the backlog against the contractual target.

**Falsified by.** A bottom-up model showing the scoped initiatives sum to materially less than 1%.
Or Phase 1 initiatives landing with measured lift well below what the remaining backlog would need
to close the gap.

**Depends on it.** The contractual success measure in `engagement.md`, and the renewal conversation
that needs to start before January 2027. Discovering this late is the worst version of the
engagement ending.

**Confidence.** Low, and untested. Reviewed 07/09/2026.

---

## A12 UK growth is the better bet than US recovery

**Superseded by A18, 18/09/2026.** Original text below, unaltered.

**Rests on.** UK now at 72% of US demand, with US non-brand demand down 40% year on year. The
inference is that UK is structurally growing rather than temporarily cyclical, and that US decline
is not recoverable through the same effort.

**Falsified by.** US non-brand demand recovering on its own, indicating a cyclical dip rather than
a structural shift. Or UK growth flattening once the current driver, whatever it is, is understood.
Nobody has established why UK is up, which makes the bet on it partly blind.

**Depends on it.** Local specific content and copy, RICE rank 2. Also the reasoning used to defer
My New Account and the multi-tour planning work, both of which were pushed partly because they
serve the declining US market.

**Confidence.** Medium. Reviewed 07/09/2026.

---

## A13 The R1 organiser role sits behind P4's booking-by-proxy path

**Rests on.** Reasoning, not observation. `personas.md` records P4 booking from a friend's emailed
shortlist and texting links to family because there is no share mechanism. R1, recorded 17/09/2026
from the private tours research, describes someone assembling a trip on behalf of a party that did
not choose it. The inference is that the person on the sending end of the proxy path is holding R1
at small scale, which would mean the role reaches into day tours and mobile, not just private tours.
No participant has been observed on both sides of that exchange. The private tours sample contained
no P4 at all.

**Falsified by.** Interviewing the sender in a proxy booking and finding they behave like a
recommender rather than an organiser: no responsibility for the party's decision, no constraint
management, no exposure if the day goes badly. Or the share and save work shipping and being used
overwhelmingly by people booking for themselves.

**Depends on it.** Any decision to design the share and save mechanics for a party leader rather
than for an individual sharing a link. Indirectly, the framing of mobile PDP layout at RICE rank 1,
which currently assumes a single fast-deciding traveller on the page. If R1 is present there, the
page is being read by someone screening against other people's constraints, which is a different
job from saying yes fast.

**Confidence.** Low. The behaviour on P4's side is itself thin, resting on one interview plus one
texted-links report, so this is an inference layered on weak evidence. Reviewed 17/09/2026.

---

## A14 The R1 organiser role is not confined to private tours

**Rests on.** R1 was found in the private tours research because that is where it is most visible,
6 of 6 participants having come through the private enquiry route. The belief that it also operates
on the scheduled catalogue rests on one documented case, the 13-guest group that dismissed Rabbie's
after Facebook groups suggested day tours only, plus the general argument that nothing in the role
definition is product specific. A party of eight booking scheduled seats faces the same group
constraints as a party of eight booking private.

**Falsified by.** Group-led scheduled bookings showing none of the role's behaviours: no single
payer, no constraint screening before the tour is chosen, no pre-booking contact asking questions
the page does not answer. Or the opposite finding, that parties above a certain size always convert
to a private enquiry, which would make R1 genuinely a private tours construct after all.

**Depends on it.** Whether R1 is used as a frame for scheduled catalogue work or kept inside the
private tours workstream. If false, the role is narrower than recorded and several implications
drawn from it, particularly the referral argument, apply to a much smaller population than assumed.

**Confidence.** Low to medium. The reasoning is sound and the evidence is one case. Reviewed
17/09/2026.

---

## A15 Group-led demand is understated in the booking data because payments are split

**Rests on.** 2 of 6 private tour bookers documented the mechanism directly: one party paid through
separate links per payer, another organiser paid the full deposit and Rabbie's then billed each
traveller individually. Both volunteered it as a positive and the mechanism works well
operationally. Average PAX per booking in the Spike analysis runs 1.59 Australia, 1.79 UK, 1.99
Canada, 2.13 USA, which would be consistent with a base of couples and would also be consistent with
larger parties being split across transactions. The two readings cannot be separated from the figures
as published.

**Falsified by.** A query against the booking data grouping transactions by shared departure, date
and lead booker, showing group-led bookings are rare rather than disguised. That is the cheap check
and it has not been run.

**Depends on it.** Any sizing of R1, and therefore any RICE reach score on an initiative aimed at
it. Also the reading of average PAX per booking in the Spike pack, which is currently the only
party-size figure the project holds and is listed as a gap in `business.md`.

**Confidence.** Medium on the mechanism existing, which is observed. Low on the size of the
distortion, which is entirely unmeasured. Reviewed 17/09/2026.

---

## A16 Growing private tour bookings is worth more than filling seats on scheduled departures

**Rests on.** Nothing established. This is the premise underneath the question "how do we grow
private tours", and it has never been examined. Private tours carry visibly higher transaction
values, one 10-day trip in the sample exceeded a $35,000 US budget, which is where the intuition
comes from. Transaction value is not margin. Scheduled departures are assumed fixed cost per
departure, which would make incremental passengers close to pure margin, while private tours carry a
dedicated vehicle, a dedicated driver, accommodation handling, and pre-sale consultant time that is
currently unpriced. Every recommendation from the private tours research adds more of that time.

**Falsified by.** A contribution comparison, private tour per departure against scheduled tour per
departure at current average load factor, both after vehicle, driver, accommodation handling and
pre-sale consultant hours. If scheduled load factor is low and its costs are genuinely fixed, filling
existing departures may beat growing a service intensive product. The comparison does not exist
anywhere in the project. `business.md` holds the general margin-by-line gap; this specific comparison
is narrower and is the one that decides the question.

**Depends on it.** Every recommendation aimed at growing private tour volume, including the planning
call, route level input into the proposal, and accommodation research with a veto window. All three
add consultant or driver hours. It also depends on the capacity gap in `business.md`, since the
scheduled side of the comparison cannot be built without load factor.

**Confidence.** Low, and it is the assumption most likely to be acted on without being checked.
Owner for the input is Alex, CGO, the same person the capacity and channel mix gaps are waiting on.
Reviewed 17/09/2026.

---

## A17 Late booking is an artefact of late targeting, not late deciding

**Supersedes A2, 18/09/2026.** The belief is unchanged. What changed is that an apparent
contradiction in the evidence turned out, on inspection, to support it.

**Rests on.** Booker interviews consistently reporting consideration windows of months that appear
in GA4 as first-session bookings. Australia showing an earlier booking pattern under different spend
timing. Safari's seven day cookie cap and cross-device identity loss both compressing observed
windows in the same direction.

**Added 18/09/2026, the lead time contradiction and its resolution.** Spike reports average lead
times of 38.8 days for the UK, 67.9 USA, 77.8 Canada and 85.2 Australia across all bookings. GA4
shows 69.3% of bookings inside 10 days. Both figures are true and they describe different
populations. The short observed window is a property of the traffic Rabbie's acquires rather than of
how the market decides: paid acquisition weighted to the final weeks selects for people already
close to purchase, so the site sees a late deciding population because that is the population being
bought. The qualitative evidence shows research and consideration running far longer, and
specifically so on multi-day. The divergence is therefore evidence for this assumption rather than
against it.

**[assumed] Independent corroboration, on an unverified inference.** Agent bookings peak January to
March and carry an ABV of £635 against Direct's £323. If the channel ABV spread is product mix
showing through channel, which `business.md` records as assumed rather than established, then the
channel selling multi-day is reaching customers months earlier than direct spend does. That is the
same claim arriving from a different direction. It rests on the agent-sells-multi-day inference and
falls with it.

**Falsified by.** Spend moved into an earlier window producing no incremental bookings over a full
season. Or traffic quality analysis showing Rabbie's paid and non-brand audiences are not
late-window by construction, which removes the selection mechanism this now rests on. Or GA4 lead
time for direct multi-day bookings alone coming back as short as the blended figure, which would
mean the late window is real for the product that carries the value and not a mix artefact.

That third test is the cheapest of the three and has not been run. It is the one to do first.

**Depends on it.** The whole Scaling Interest recommendation and the marketing timing argument in
the August deck. Attribution window design for any multi-day test. If false, current spend timing is
correct and the drop-off problem is entirely on-site.

**Confidence.** Medium, unchanged, and now for a narrower reason. The mechanism is better explained
than it was and one apparent contradiction has resolved in its favour. The size of the recoverable
early window is still unmeasured, which was the original reason for Medium and remains the only one.
Reviewed 18/09/2026.

---

## A18 UK growth is the better bet than US recovery, and it buys the lowest value customers in the base

**Supersedes A12, 18/09/2026.** The bet is unchanged. The price of it is now known and was not
before.

**Rests on.** UK now at 72% of US demand, up from 54%, with US non-brand demand down 40% year on
year. The inference is that UK is structurally growing rather than temporarily cyclical, and that US
decline is not recoverable through the same effort.

**Added 18/09/2026.** UK is simultaneously the largest market by volume, the weakest on repeat, and
the lowest on value. 83.6% of UK customers book once, against 79.0% USA, 76.9% Australia and 76.0%
Canada. UK ABV is £181, against USA £226, Australia £271 and Canada £310. UK also has the shortest
lead times at 38.8 days. Source: Spike, sections 2, 37 and 41.

**Spike's position, adopted.** Their reading is that UK retention is the single biggest lever,
because the largest market with the weakest repeat rate moves the most absolute customers for a
modest improvement. That is recorded here as their recommendation and taken.

**The tension in their own deck, which they do not reconcile and which should be held.** The same
pack recommends leaning into Canada and Australia on materially higher ABV and CLTV. The two
recommendations pull in opposite directions and nothing says which wins. Most absolute customers is
a volume argument. At £181 against £310, more UK customers can be worth less than fewer Canadian
ones. That arithmetic has not been done by anyone.

**The retention half of this bet is currently blocked, and not by strategy.** Email marketing
permission on new bookers is 8.05% in 2026, against 96 to 99% on every cohort to 2020. A UK
retention programme cannot run against a base that cannot be emailed. See the Reachability section
in `business.md`. It may be a tracking convention change rather than a real consent collapse, and
nobody knows which. Resolve that before acting on this assumption at all.

**Falsified by.** US non-brand demand recovering on its own, indicating a cyclical dip rather than a
structural shift. Or UK growth flattening once the current driver is understood, and nobody has
established why UK is up, which makes the bet partly blind. Added 18/09/2026: a lifetime value
comparison showing UK volume growth at £181 and a 16.4% repeat rate returns less than equivalent
effort spent on Canada or Australia.

**Depends on it.** Local specific content and copy, RICE rank 2. The reasoning used to defer My New
Account and the multi-tour planning work, both pushed partly because they serve the declining US
market. Added: any UK retention or CRM programme, which also depends on reachability being fixed
first.

**Confidence.** Medium on the demand direction, unchanged. Low on this being the best use of the
effort, which is a new question and the part now genuinely in doubt. Reviewed 18/09/2026.

---

## A19 UK growth is the better bet than US recovery, now against the client's own reading

**Supersedes A18, 24/09/2026.** The bet is under more pressure than at any point since it was
written, and Rabbie's management has now stated the opposite position.

**Rests on.** UK at 72% of US demand, up from 54%, with US non-brand demand down 40% year on year.
The UK site addressing a customer who already knows Scotland as a first-time visitor, which makes UK
conversion look fixable rather than inherent.

**Added 24/09/2026.** YTD, the US converts at 1.86% and the UK at 0.78%. On roughly equal sessions,
962,233 against 869,116, the US produces 17,849 bookings and the UK 6,786. The US is 42.6% of Direct
bookings, the UK 16.2%. Management's line on the slide is "quality, not volume, is the lever". Source:
State of the Nation, slide 4. With UK ABV at £181 against £226, a US booking is worth about a quarter
more and arrives from a session about two and a half times as likely to convert.

**Two things keep this open rather than falsified.** First, the UK conversion gap is the thing the
bet claims is fixable. A low UK rate is consistent with a site aimed at the wrong UK customer as well
as with a low-quality market, and nothing yet separates the two. Second, both demand figures under
the original bet, 72% and -40%, come from the August review. Whether they are platform or search
volume figures is not recorded. If platform, they sit inside the 11/05/2026 to 22/09/2026 tracking
bug window.

**Falsified by.** Everything listed under A18. Added: the UK copy work, RICE rank 2, shipping and UK
conversion staying materially below US. That would show the gap is the market, not the site.

**Depends on it.** Local specific content and copy, RICE rank 2. The deferral of My New Account and
multi-tour planning work, both pushed partly because they serve the US. Any UK retention programme.
`strategy/2026-09_uk-versus-us-market-bet.md`, which now needs a superseding memo.

**Confidence.** Low, down from medium on demand direction. The client's own leadership has taken the
other side on stronger conversion evidence than the bet rests on. Reviewed 24/09/2026.

---

## A20 Growing private tour bookings is worth more than filling seats on scheduled departures

**Supersedes A16, 24/09/2026.** The belief is unchanged and still untested. What changed is the size
of what rests on it.

**Rests on.** Nothing established, as under A16.

**Added 24/09/2026.** Private tours are £3.9m on the books YTD, +24% year on year, and the 2027
forward book is +116.5% against same time last year, the largest forward gain of any line in £.
Source: State of the Nation, slides 2 and 6. Management also states a fixed cost base and a 2026
focus on filling inventory already secured, slide 6. That is the scheduled side of the comparison in
their own words. Private tours grow volume by adding dedicated vehicles, drivers and consultant
hours, which is the opposite of filling secured inventory. The two strategies sit on the same slide
and nobody has compared them.

**Falsified by.** As A16. The contribution comparison, private against scheduled per departure at
current load factor, after vehicle, driver, accommodation handling and consultant hours.

**Depends on it.** As A16. Added: any 2027 growth target set on the private tour forward book.

**Confidence.** Low. The risk named under A16, that this is acted on without being checked, is now
more likely, because the forward book will pull resource towards private tours on its own. Reviewed
24/09/2026.

---

## A21 The guest details to payment loss is accumulated doubt, not a guest details problem

**Added 24/09/2026.** Joe's working reading of the 53% loss between guest details and payment.

**Rests on.** The step is the moment of commitment. Known unanswered questions reach it unresolved:
accommodation is invisible until the booking flow, cancellation terms are not surfaced prominently,
customers are confused by the concierge fee, and multi-day requires full payment upfront. Consistent
with the standing judgement that late-stage surprises cause abandonment.

**Falsified by.** QW-23 finding that a material share of the loss is untracked returns from a payment
provider. Or SP-15: a summary of total price, cancellation terms, inclusions and payment options at
guest details producing no reduction in loss. Or the loss staying flat after SP-25 moves the same
information onto the tour page. A large loss concentrated on sessions that saw a price change at the
total would point to price shock instead.

**Depends on it.** SP-25, SP-15, the booking flow changes in LI-02, and the case for deposits (LI-05)
in `work/2026-09-24_2027-delivery-plan_v5.md`.

**Confidence.** Medium. The mechanism fits the evidence and nothing has tested it. The figure itself
is blended across products and needs a tracking check. Reviewed 24/09/2026.

---

## Prompts for finding your own

Write these down as you notice them rather than trying to list them all now.

- What did the brief take as given that nobody has checked?
- What are you confident about with no data behind it?
- What would the client be most surprised to hear was uncertain?
- If this engagement fails, what will have been wrong?
