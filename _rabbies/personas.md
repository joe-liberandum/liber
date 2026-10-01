# Personas: Rabbie's

Who Rabbie's customers are, grounded in research. Used by the CRO and UX work in `design/`,
`analysis/`, and any `strategy/` memo.

**Not to be confused with `flock-hub-business/context/personas.md`.** That file describes Flock Hub's
buyers. This one describes Rabbie's travellers. Same client name in two contexts, entirely different
people, and the two must not cross.

## Rules

Every attribute is marked `[observed]` or `[assumed]`. Observed means it came from research, with the
study and sample stated. Assumed means it was reasoned out or inherited from the brief.

Assumed attributes that work depends on get an entry in `assumptions.md` with a falsification
condition.

No personal data. Composites only, no real names or contact details. Raw data stays outside version
control, referenced from the study's `SOURCES.md`.

Update rather than replace, noting what changed and when.

---

## Source research

Four waves, layered against 12 months of GA4 session and revenue data by tour.

| Wave | Segment | Participants | Date |
|---|---|---|---|
| 1 | A, bookers | 26 sessions with transcripts, plus 1 participant with no file held. UK/US/Canada, single and multi-day | Nov 2025 to Apr 2026 |
| 2 | C, competitor bookers | 6 who booked with a competitor and had some Rabbie's knowledge, UK/US/Canada. **No source files held** | May to Jun 2026 |
| 1 | Competitor bookers inside the A window | 2 sessions, established from transcript framing. Segment label unconfirmed | Mar to Apr 2026 |
| 2 | D, active planners | 6 active planners with no Rabbie's knowledge, recruited via People For Research | 3 to 4 Jun 2026 |
| n/a | Post-tour | 1 completed UK day tour customer, booked by proxy | 18 Jun 2026 |
| 3 | **B, site and cart abandoners** | **Not recruited.** See `strategy/2026-09_abandoner-research-recruitment.md` | Outstanding |

Wave 1 built the original four personas. Waves 2 tested them against people who did not buy.

**Counts rebuilt 07/09/2026 from the files.** 35 sessions with transcripts held across all waves. The previously quoted 18,
21 and 23 each counted something different; the deck's 18 cannot be reconstructed and has been used
externally. Arithmetic and full register in `research/SOURCES.md`.

**Segment membership is not exclusive, and that matters for the persona set.** At least one
participant is both A and C, having booked Rabbie's for one leg and competitors for others on the
same trip. That is the Purposeful Adventurer's defining behaviour showing up in the sampling frame
itself. It means segment counts cannot be summed, and it is a small piece of independent support for
the split-booking behaviour P2 describes.

**Segment D date unresolved.** Recorded as June in two documents, recalled as July. Confirm against
the recruiter's records.

Anything listed here with no study behind it is a working hypothesis, and should say so.

---

## Segmentation

**Honest note on method.** These four were derived inductively from Segment A interviews, not built
by picking axes first. The axes below are read back off the set. That is worth knowing, because it
means the axes were never tested as the right ones.

Read back, three axes separate the four, not two:

- **[observed] Planning horizon, and where the decision happens.** The strongest separator.
  6 to 12+ months and off-site (P1) versus a single session close to the day (P4). This is the axis
  the whole early-window marketing argument rests on.
- **[observed] Prior relationship.** First-time versus repeat. P3 exists on this axis alone and
  behaves nothing like the rest in a funnel: already decided, shopping inside the site rather than
  choosing between operators.
- **[observed] Trip role.** Whether the tour is the trip skeleton (P1) or one leg of a
  self-organised trip (P2). This is the only thing separating P1 from P2, and it is the least
  directly observed of the three.

**Origin is a correlate, not an axis.** US and Canada cluster on long horizons, UK on short. That
falls out of the other axes rather than driving behaviour independently, and treating it as an axis
would produce a geography-shaped persona set that does not help a CRO decision.

**The weakness worth naming.** P1 and P2 separate on the least-evidenced axis. Segment D confirmed
P2's product gap while only weakly confirming its behavioural profile, which is consistent with the
separation being thinner than the set implies.

---

## P1 The Meticulous Planner

**One line.** Deep researcher who builds the whole trip around the tour, with the brand decision
usually made off-site weeks before they arrive.

**Source.** 8 core interviews from Segment A, strengthened by 2 of 6 in Segment D. 90% research
confidence. Status: strengthened.

### Context

- **[observed]** US and Canada. Multi-day bias. Roughly 35% of sessions, duration-weighted. Books
  6 to 12+ months out.
- **[observed]** Typically booking with a partner or family, so the decision is co-made over weeks.
  Not booking alone even when browsing alone.
- **[observed]** Discovers Rabbie's through third-party trust: Facebook travel groups, Reddit,
  influencers, blogs, Rick Steves. Arrives at the site to confirm a decision already forming, not to
  discover.
- **[assumed]** Desktop-primary for the research sessions. Inferred from session length and
  comparison behaviour, not measured.

### What they are trying to do

- **[observed]** Total trip confidence. The entire trip handled and de-risked, accommodation
  included, before committing money months ahead. Value is measured in confidence, not price.
- **[observed]** When researching months ahead, see real, dated, attributed reviews, so the brand's
  own claims can be trusted.
- **[observed]** When booking with family, save and share a shortlist so the group can decide
  together.
- **[observed]** Will delegate logistics, but only if the process visibly feels managed. Silence
  reads as nothing happening.

### Where it breaks

- **[observed]** Navigational entry points do not fit their mental model and have to be re-learned.
  Entry points they expect are departure city and interests.
- **[observed]** Filtering does not surface tours matching specific locations or stops, only
  destinations.
- **[observed]** Tour end dates are not shown, so days are counted manually to chain tours
  back-to-back. One customer emailed to check whether two tours fitted together.
- **[observed]** No central place to plan or compare multiple tours against a date range. Comparison
  is done with spreadsheets, tabs, and hand-drawn checklists.
- **[observed]** Months of silence between booking and accommodation confirmation. One customer went
  back through her email to check the booking was real.
- **[observed]** No mobility or accessibility information on the page. 1 of 6 in Segment D spent a
  sustained part of her session hunting for it for an 85-year-old traveller and concluded she would
  have to phone. Support hours do not cover North America.
- **[observed]** No way to register interest in a tour without published dates.

### What they do instead

- **[observed]** Reads the worst reviews first, specifically to filter out paid praise.
- **[observed]** Keeps a trip budget spreadsheet, and records booking reference and currency
  conversion into it by hand.
- **[observed]** Phones, or plans to phone, when the page will not answer a qualification question.
- **[observed]** Considers a travel agent as an alternative route to the whole trip. 2 of 6 in
  Segment D. This is new and the persona under-weights it.

### Dissent

One Segment D participant strengthens the persona on the numbers-and-logistics dimension while
diverging sharply on planning horizon and brand loyalty, so the research-depth trait and the
long-horizon trait do not travel together as reliably as the profile implies.

The travel agent finding is dissent against the persona's core premise. If the agent is a live
competitor to the website itself, then "the brand decision is made off-site" understates the
problem: the whole channel decision may be made off-site.

### What we do not know

Whether this persona ever abandons, and where. Every instance in the sample either booked or was
still deciding when interviewed. The 35% of sessions figure is duration-weighted GA4 attribution to
the persona, not a measured population.

### Depends on this persona

Owned reviews (rank 4). End dates on calendar (rank 3). Surface accommodation on PDP. Save and share
mechanics, currently deferred. The entire early-window marketing argument in
`strategy/2026-09_late-booking-is-a-targeting-artefact.md` rests on this persona more than the other
three combined.

---

## P2 The Purposeful Adventurer

**One line.** Destination-led, time-efficient traveller using Rabbie's for one leg of a bigger,
self-managed trip, whose loyalty is to the place rather than the brand.

**Source.** 7 core interviews from Segment A, partially corroborated by 3 of 6 in Segment D. 70%
research confidence. Status: mixed. Gap confirmed, profile unverified.

### Context

- **[observed]** US, Canada and UK. Solo or pair. Roughly 20% of sessions. Multi-stop,
  self-organised itineraries.
- **[observed]** Travelling for an event or occasion: a wedding, a gig, visiting friends. Books
  around it, then fits tours into the gaps.
- **[observed]** Arrives with a departure city and days to fill, and often a specific interest list
  written elsewhere. Interrogates every tour against it.
- **[observed]** Will split-book across operators without hesitation if Rabbie's does not cover the
  right route or duration.

### What they are trying to do

- **[observed]** An efficient, well-matched leg that fits a self-organised trip. Ideally a shorter
  multi-day option that does not over-commit their time.
- **[observed]** When based somewhere for a few days, find a 1 to 3 day option to explore without
  over-committing.
- **[observed]** When planning a multi-stop route, see which tours share stops, so destinations are
  not duplicated.
- **[observed]** Starts with shorter, low-commitment tours and will upsell to longer ones if
  confidence in Rabbie's grows.

### Where it breaks

- **[observed]** The catalogue pushes toward longer tours. The 3 to 4 day mid-length option does not
  exist. Confirmed independently by 2 of 6 in Segment D, one of whom said she would rather do small
  things within a 3 to 4 day stay than a 3-day tour.
- **[observed]** The route map, their primary decision tool, is not aligned with the itinerary text.
  Stop indication does not match, causing frustration. The map is unlabelled and non-interactive.
- **[observed]** Tour comparison is manual, and stops get accidentally duplicated across legs.
- **[observed]** The guide, the reason they would rebook, gets almost no space on the product page.
- **[observed]** Search dead-ends end discovery early. This persona has lower willingness to keep
  searching than the others.
- **[observed]** No way to register interest in a tour without the dates they need.

### What they do instead

- **[observed]** Books the missing leg with a competitor. One Segment A participant booked a 5-day
  Highland tour elsewhere after finding no 2-night option.
- **[observed]** Compares tour maps by hand.

### Dissent

**This is the persona with the most recorded dissent, and it is structural.** Segment D strongly
confirms the mid-length duration gap but only weakly supports the destination-wish-list,
map-as-primary-filter decision pattern. One participant is the closest fit, treating the map as a
decision tool and criticising its labelling. The rest confirm the product gap without exhibiting the
behaviour.

Read plainly: the gap is real and the persona around it may not be. It is possible the duration gap
is felt across several personas and has been attributed to a profile that does not independently
exist.

### What we do not know

Whether the destination-led map-first behaviour is a real cluster or an artefact of the original
sample. This is the highest-value question in the set, because it determines whether P2 is a persona
or a need state, and P1 versus P2 separation depends on the answer.

### Depends on this persona

The 3 to 4 day duration recommendation in `strategy/2026-09_mid-length-duration-gap.md`, which is
described as the highest long-term revenue opportunity on the account. Map improvements. Compare
tours, blocked on the tour stop data check. Guide module.

Note the exposure: the largest claimed revenue opportunity rests on the least verified persona
profile. The demand evidence is stronger than the persona evidence, which is why that memo
recommends evidencing the gap rather than the persona.

---

## P3 The Trusted Returner

**One line.** Loyal repeat customer who recruits new customers unpaid, and whose competitive
decision is closed before they open the site.

**Source.** Segment A, including one repeat customer interviewed while actively in market (Carrie H,
22 Apr 2026), identified 07/09/2026 and not counted in the original synthesis. 65% research
confidence, the lowest of the four. Status: indirectly supported, and now directly supported in part.

**Correction, 07/09/2026.** This persona was previously recorded as having no direct participant
quote in the dataset. That was wrong. Carrie H is a returner, observed in market rather than
reconstructing afterwards, which is the only such case in the entire evidence base. The confidence
rating has not been revised, because one participant does not move it on its own, but the stated
reason for the low rating no longer holds and should be restated before the rating is quoted again.

### Context

- **[observed]** US, with some UK. Repeat bookers, some with 15-year relationships with the brand.
- **[observed]** Treats the site as a curated menu and often books multiple tours in a single
  session.
- **[observed]** Engages with Rabbie's owned social channels. Carrie H follows on both Facebook and
  Instagram, the only participant in the evidence base who reports doing so.
- **[assumed]** Sits at the top of a loyalty funnel fed by P4. Today's day-tripper becomes tomorrow's
  returner. Reasoned from the two personas' shapes, not traced through data.

### What they are trying to do

- **[observed]** When returning, be recognised and skip the cold start so rebooking feels
  effortless.
- **[observed]** When bringing a friend to Rabbie's, refer and share easily so the advocacy is
  rewarded and tracked.
- **[observed]** Actively coaches new customers through the booking process, unpaid and untracked.

### Where it breaks

- **[observed]** Filter unreliability is acutely damaging here. A loyal customer cannot find a tour
  they know exists. Some gave up.
- **[observed]** No repeat-customer recognition. Every booking starts from scratch.
- **[observed]** No notify-me for tours without published dates.
- **[observed]** The advocacy loop is entirely unstructured. No referral mechanism, no shareable
  wishlist.
- **[observed]** End-of-tour drop-off logistics are unclear when a tour ends in a different city.

### What they do instead

- **[observed]** Recommends by word of mouth, unprompted, in Facebook travel groups. One Segment A
  participant reported seeing people ask about Rabbie's in a Scotland travel group at least a dozen
  times.

### Dissent

**"Not evaluating, shopping" is too strong.** Carrie H describes checking whether Rabbie's runs a
tour from where she is, then comparing on Viator, TripAdvisor and Yelp, and returning to Rabbie's
about nine times in ten. She does evaluate. She converges. That is a materially different design
brief: the competitive comparison still happens, it just reliably resolves in Rabbie's favour, which
means it can also stop doing so.

Segment D could not test this persona by design, since all participants were new visitors. Two
adjacencies were noted there: the advocacy engine is latent in the new-visitor sample, and 1 of 6
raised the absence of an account and app unprompted as the reason the post-booking relationship
feels thin.

### What we do not know

Almost everything about the mechanism. The advocacy behaviour is observed; whether a referral
programme would capture it, distort it, or kill it is not. Advocacy that people currently give
freely can be damaged by formalising it, and nothing in the evidence base speaks to that risk.

How large the segment is. **Corrected 17/09/2026.** This previously read that repeat booking rate is
not tracked. It is tracked, and the Spike customer insights pack measured it in July 2026: 89.3% of
customers have booked once, roughly 3% of any year's bookers return the following year, and UK is the
weakest market at 83.6% booking once. See `business.md`.

The correction does not help the persona, it hurts it. P3 is real and it is very small. Roughly half
of apparent second bookings are the same holiday split into two transactions, and 37 to 41% of second
bookings are made on the same day as the first, so the genuine return rate is lower again. Spike's
own segmentation counts 1,346 Loyal customers at six or more bookings against 281,902 First Timers.
The four initiatives that depend on this persona are all cheap, which was already the argument for
doing them. It is now the only argument. Nothing expensive should be built on P3.

Whether owned social is a real retention channel or one person's habit. Carrie H is a single case,
but she is the only evidence in the file that Rabbie's owned channels reach anyone at all.

### Depends on this persona

Referral mechanism (rank 7). Post-tour email and loyalty sequence (rank 5). My New Account, deferred
on dev capacity. Loyalty recognition, deferred.

All of these are cheap, which is fortunate, because the persona underneath them is the weakest in
the set.

---

## P4 The Pragmatic Day-Tripper

**One line.** Spontaneous, fast-deciding, low-commitment booker who goes from zero to booked in a
single session and becomes a vocal advocate after one day on the van.

**Source.** Segment A, corroborated by 1 of 6 in Segment D and by the post-tour interview. 78%
research confidence. Status: strengthened and reframed.

### Context

- **[observed]** UK primarily, plus international visitors booking in-destination.
- **[observed]** The tour is a low-commitment add-on to a trip already organised. Often a reactive
  decision: a free day needs filling.
- **[observed]** Mobile is the primary device. Most paid social traffic is mobile.

### What they are trying to do

- **[observed]** When landing on a tour page on a phone, see reviews, group size and the map at
  once, so they can say yes fast.
- **[observed]** When a friend sends tour links, book and share from that shortlist so the group
  decision stays simple.
- **[observed]** Scans visuals and review volume for persuasion. Does not read copy in depth.
  Decides on whether the brand matches expectations.

### Where it breaks

- **[observed]** The homepage search widget demands a date before the customer has been persuaded.
  3 of 6 in Segment D hit commitment friction here.
- **[observed]** Mobile hierarchy buries reviews, group size and map below the fold.
- **[observed]** No video content of the tour or the guide, so there is nothing to judge the feel
  against.
- **[observed]** No way to save or share a tour for proxy or group decisions.
- **[observed]** Search dead-ends end the session entirely, with no fallback to contact. Higher
  churn risk than the other personas. The post-tour interviewee said she would simply stop looking
  rather than get in touch.
- **[observed]** No awareness the multi-day catalogue exists, even among satisfied day-trippers. The
  post-tour interviewee, primed to rebook, did not know it was there.

### What they do instead

- **[observed]** Books from a friend's emailed shortlist, bypassing reviews, comparison and most
  persuasion surfaces entirely. This is the booking-by-proxy path.
- **[observed]** Texts links to family because there is no share mechanism.
- **[observed]** Attributes roughly 90% of experience quality to the guide, post-tour.

### Dissent

**The reframe is the dissent, and it matters.** The persona is described as converting within a
single session on visuals and review volume. In Segment D, review thinness actively blocked that
fast conversion: 1 of 6 moved from interested to a firm no almost entirely on the review section.

So the speed is conditional on social proof being present, not unconditional. A thin unattributed
review feed does not slow this persona down, it stops them. That is a materially different design
brief from "make it fast".

### What we do not know

Whether the loyalty-funnel link to P3 is real. It is assumed, and if false, the case for investing
in day-tripper experience as an acquisition channel for repeat business weakens considerably.

Whether booking-by-proxy is common or a single vivid case. It rests on one interview plus one
texted-links report.

### Depends on this persona

Mobile PDP layout (rank 1, the highest on the backlog). Owned reviews (rank 4). Browse-without-dates
homepage entry. Save and share mechanics. Post-tour cross-sell into multi-day.

Note that rank 1 also depends on an unverified traffic-quality assumption, A4, which is about the
channel rather than the persona.

---

## Roles

A role is not a persona. A persona describes who someone is and how they decide. A role describes a
job someone is holding on this particular trip. The same person can hold it on one booking and not
the next, and any of the four personas can be holding it. Roles are recorded here because they
change the design brief without changing the persona set.

Roles are marked `R<n>` to keep them visually distinct from `P<n>`. There is currently one.

**Why this is a role and not a fifth persona.** Added 17/09/2026. The four personas separate on
planning horizon, prior relationship and trip role, all of which are shopping behaviours. The
Appointed Organiser cuts across all three. In the private tour sample, the same behaviour appeared
on a 12-month planner and a repeat customer alike, and the participants mapped to two personas at
once rather than forming a fifth cluster. Adding it to the persona set would have broken the set's
one method. Layering it over the set keeps both usable.

---

### R1 The Appointed Organiser

**One line.** The person who has been handed responsibility for a party of four to sixteen travellers
with incompatible needs, who is buying delegated expertise and blame reduction rather than a premium
product, and who will choose the operator that tells them what to do first.

**Source.** `research/2026-Q3-pvt/findings.md`, 6 private tour bookers, Sep 2026, F1. 5 of 6 held the
role. Corroborated indirectly by the 13-guest group miss recorded under group and private hire.

**Evidence strength.** Strong that the role exists and strong on what it wants, on 5 of 6 with
consistent and specific reasoning. No percentage confidence is given, because the persona percentages
come from a different method and a different sample and the two should not be read as comparable.

#### What defines the role

- **[observed]** Responsibility is delegated to them, not chosen. Extended family, retired friends,
  in-laws, a group that likes to travel and does not like to plan.
- **[observed]** They are usually the payer or part-payer at deposit stage, and frequently pay for
  everybody before the party is billed back.
- **[observed]** The purchase removes variables from a group rather than adding quality to a trip.
  The constraints named were composition, not taste: mobility, diet, age spread from 11 to 80s,
  motion sickness, a refusal to drive on the left.
- **[observed]** They carry the reputational risk personally. "I'm the guy that is gonna take the
  flak from the other 15 people."
- **[observed]** They frequently cannot answer an open brief and want to be told. Asked what he
  wanted to do, one organiser's answer was that he did not know and Rabbie's should tell him.

#### Detection, which matters more than any script

**[observed]** Three organiser states appeared in six interviews and they need different handling.
One wanted creation, having no wish list at all. One wanted correction, arriving with a self-built
itinerary and valuing being told he was doing too much. One wanted neither, using a published Rabbie's
tour as a skeleton and wanting only the arrangements made. A single improved opening script serves
one of the three and irritates the other two. The operational requirement is a qualification
question, not a template.

**[observed]** Party size, age spread and the presence of a named constraint are the signals
available before any conversation, and all three arrive in the enquiry form or the first reply.

#### What changes when the role is present

- **[observed]** The first reply becomes the product demo. Where a live competitor existed, 2 of 2
  switched to Rabbie's on proposal specificity, not on the website.
- **[observed]** The website drops out of the decision almost entirely. 4 of 6 spent under ten
  minutes on site before making contact.
- **[observed]** Group needs are communicated in prose inside email, and that is where they fail.
  4 of 4 multi-day organisers had an accommodation problem, four different problems.
- **[observed]** Price stops being the barrier and legibility becomes it. 5 of 6 did not treat price
  as a barrier. This is measured only on people who converted and cannot speak to anyone who did not.
- **[observed]** Voice contact is wanted once, at the start, on multi-day trips with no fixed plan.
  Not wanted by either single-day booker.

#### How it overlays the four personas

| Persona | Overlay observed | Note |
|---|---|---|
| P1 Meticulous Planner | **[observed]** 2 of 6, JT and KA | The research depth is the persona. The group responsibility is the role. Spreadsheets, refundable bookings and six months of planning are P1 behaviours applied to a party rather than a couple. |
| P3 Trusted Returner | **[observed]** 3 of 6, AM, HC, CP | The strongest overlay in the sample and the one with the most commercial weight. A returner who is also an organiser converts an entire party and is the referral route to the next one. |
| P2 Purposeful Adventurer | **[assumed]** Not observed | No participant held both. The role is plausible on a large-family or special-event variant of P2, which is where the private-tour pull was already filed. Untested. |
| P4 Pragmatic Day-Tripper | **[assumed]** Not observed in this study. `assumptions.md` A13 | P4's documented booking-by-proxy path has an organiser on the sending end: someone assembles the shortlist and texts the links. That person is holding this role at small scale. The link is reasoned, not traced. |

**The role is not confined to private tours.** `assumptions.md` A14. It was found there because
private tours is where it is most visible. Nothing in the evidence says a party of eight booking
scheduled seats is behaving differently, and the group and private hire segment miss suggests the
same role losing business on the scheduled catalogue. Treating R1 as a private-tour-only construct
would repeat the mistake of filing the behaviour under a product rather than under a customer. One
documented case supports it, which is thin.

#### Why the role is invisible in the booking data

**[observed]** Group payment mechanics split one organiser's decision into several transactions.
2 of 6 documented it: one party paid through separate links per payer, another organiser paid the
whole deposit and Rabbie's then billed each traveller individually. Both were volunteered as
positives and the mechanism works well.

**[assumed]** `assumptions.md` A15. The consequence is that average PAX per booking, which runs
1.59 to 2.13 across the four major markets in the Spike analysis, cannot be used to size this role.
A 16-person decision can present as 16 single-passenger bookings. Nobody has checked whether it
does, and the check is cheap: group transactions by shared departure, date and lead booker. Until
that runs and product tags on sales land, this role has no measurable size, which puts it in the
same position as P3.

#### Dissent

**[observed]** 1 of 6 does not hold the role at all. MS booked for a party of two, had no group to
manage, and bought privacy and control rather than delegation. She is the clearest evidence that
private tour interest and this role are separate things.

**[observed]** 1 of 6 splits the role in two. HC did the organising but her grandparents were the
payers, so buyer and organiser were different people. No other case had this, and it is the variant
most likely to recur in a UK-resident-hosting-visitors pattern.

#### What we do not know

- Whether anyone holding this role enquires and does not book. All 6 converted. This is the same
  structural gap as Segment B and it is not closed by this study.
- How large the role is, in either private or scheduled bookings. See above on payment splitting.
- Whether it holds outside North America. 5 of 6 are North American and the sixth is a UK resident
  hosting Americans.
- Whether the two-person private buyer is a second role, a need state, or just MS. One participant.
- Whether the referral mechanism the role implies, one organiser recruiting the next party, shows up
  in real repeat booking data. It is currently an inference from one participant who has run group
  trips for twelve years.

#### Depends on this role

Structured group needs capture. Accommodation named early with a veto window. The scoped discovery
call for multi-day enquiries. Opening the first reply with a recommendation rather than an open
question. All four are process changes and none of them is a website feature.

Also touches P3's referral mechanism, rank 7, which is currently scoped around an individual
advocate rather than a party leader, and the save and share mechanics, which are currently scoped
around an individual sharing a link. Both worth revisiting against this role before they are built.

**Whether any of it is worth doing is a separate question, logged as `assumptions.md` A16.** Every
process change R1 implies adds pre-sale consultant or driver hours, and no comparison exists between
the margin on a private tour and the margin on filled seats on a scheduled departure.

---

## Not personas

**Private tours buyers.** Decided, recorded, and not to be relitigated. The private-tour pull is a
need state layered on the existing four, not a fifth persona. The people drawn to it diverge on
discovery, decision pattern and value exchange, sharing only the private-tour interest. Primary home
is P1, secondary thread is P2, the large-family or special-event group. Only 2 private-tour buyers
have ever been interviewed, so this exclusion should be revisited if the private tours research
runs.

**Revisited 17/09/2026, exclusion upheld and the reason sharpened.** The private tours research has
now run, 6 bookers, Sep 2026. It confirms that private tour interest is not a persona. What it found
underneath is a role, not a need state: 5 of 6 were organising for a party, 1 of 6 was a couple
buying privacy, and the participants mapped to two existing personas at once rather than forming a
fifth cluster. The role is recorded as R1 above. The original entry's instinct was right and its
label was wrong. A need state describes what someone wants on this trip. R1 describes a job someone
has been given, which is what actually changes the brief.

**The AI-and-social-first researcher.** Flagged in Segment D as a candidate fifth persona or a
modifier on the existing four. 3 of 6 led with AI overviews, Reddit, TikTok, Instagram and creator
content. Younger and more channel-diverse than the existing set assumes. **Not yet decided.** Held as
a modifier rather than a persona, because the behaviour is a discovery channel shift that cuts across
all four rather than a distinct decision pattern. Worth revisiting if it recurs in the next wave.

**Trade, agent and charter bookings.** Outside a consumer funnel engagement. Not researched, not
scoped, not covered by any persona here.

### Segments with no persona, which is different from being out of scope

These drive initiatives and their reach and impact scores are guesses:

- **Late availability bookers.** Marked "To discover". Never interviewed. Reach scored 2 of 5 for
  that reason alone, on a page about to receive top-of-navigation traffic.
- **Group and private hire.** New segment. One documented direct revenue miss: a 13-guest group
  dismissed Rabbie's because Facebook groups suggested day tours only.
- **Site and cart abandoners.** Segment B, scoped and not recruited.

---

## Open questions for the next study

1. **Does the P2 behavioural profile exist independently of the duration gap?** Highest-value
   question in the set. Determines whether P1 and P2 separate at all.
2. **Where does P1 abandon?** No instance of this persona leaving has ever been observed.
3. **Would formalising P3's advocacy capture it or damage it?** No evidence either way, and four
   initiatives assume the former.
4. **Is booking-by-proxy a pattern or a case?** Currently one interview and one adjacent report.
5. **Is the AI-and-social-first behaviour a modifier or a persona?** Needs a second wave to see
   whether it recurs.
6. **Do late availability bookers behave like P4 with a shorter horizon, or like something else?**
   The cheap test is 2 to 3 UK last-minute booker interviews in an April to June window.

Feeds `research/plan.md`.

---

Last reviewed: 07/09/2026
