# Failures

What went wrong, why, and what would have caught it. One file per repository, or per client where
the failure belongs to a specific engagement.

This is the file that separates a system holding your files from one holding your judgement.
`decisions.md` records what you chose. `assumptions.md` records what you believe. Neither records
what you got wrong, and across four contexts the same mistakes recur in different clothes.

Append-only. Never edit or delete an entry. A failure that later turns out to have had a different
cause gets a new entry referencing the original.

## What belongs here

Anything that cost time, money, credibility, or trust and had a cause you could name afterwards.
Scope disputes, work delivered that missed the brief, a recommendation that did not survive contact
with the data, a deadline missed for a reason that was visible in advance, a tool or process choice
that had to be reversed.

## What does not

**Never record a person as the cause.** "Scope was agreed on a call and never written down" is a
root cause you can act on. "<Name> changed their mind" is blame, and it makes the log useless for
the thing it exists to do. Clients and partners change their minds; the failure is in what you did
not have in place when they did.

Ordinary uncertainty is not failure. A hypothesis that turned out wrong after being properly tested
is a finding, and it belongs in `findings.md` or as a falsified assumption.

For client repositories, be careful with failures that are the client's rather than yours. Those are
sensitive in a way your own mistakes are not, particularly where a partner sits between you and the
client. Record them only where you need to, and record the mechanism rather than the party.

## Format

## F<n> Short description

**Date.** When it happened, or the period over which it became clear.

**What happened.** Two or three sentences. Observable facts.

**Root cause.** Why. Not the trigger, the underlying condition that made the trigger possible.

**Would have caught it.** The check, habit, or document that would have surfaced this in time. This
is the field that does the work. Everything else is a record; this is a control.

**Cost.** Time, money, or trust. Rough is fine. It determines whether the prevention is worth its
own overhead.

---

## F1 Abandoner recruitment has not worked, and the method was the reason

**Date.** Planned from the start of the research programme. Visible as a blocker from 06/2026
onwards.

**What happened.** Segment B, site and cart abandoners, was scoped as part of the research
programme alongside Segment A (26 sessions held), Segment C (6 competitor bookers) and Segment D (6 active
planners with no Rabbie's knowledge, recruited through People For Research). A, C and D were all
fielded. B has not been recruited. The method for all four segments was the same: moderated video
calls of around 45 minutes.

**Root cause.** The recruitment method was chosen once for the programme and applied to every
segment. It works for people with a live relationship to Rabbie's and fails for the one segment
defined by not having one. Asking someone who already discounted the brand to give up 45 minutes to
explain why is a barrier inherent to the method, not to the recruiter or the incentive. The segment
whose recruitment was hardest was also the one where the method was least examined before
committing to it.

**Would have caught it.** Assessing recruitment feasibility per segment at research design, not per
programme, and asking of each one: what does this segment have to give up to take part, and what do
they get. Piloting the method on the hardest segment first rather than last would have surfaced the
mismatch when there was still time to change approach.

**Cost.** Segment B is still open. Nine initiatives carry confidence ratings capped by its absence,
including Deposits at 0.55, currently being scoped, and late availability, whose persona is marked
"To discover" on a page about to receive top-of-navigation traffic. The fix, AI-moderated interviews
triggered at signs of abandonment via Flock Hub, removes the barrier by catching people in the
moment rather than asking them back. It is on the research roadmap as the AI interviews pilot. That
is the right answer, and it arrived after the constraint had already shaped nine estimates rather
than before.

---

## F2 A chart was built, presented, and then withdrawn because the segmentation could not support it

**Date.** 08/2026

**What happened.** Time from first visit to booking was charted, split by day-tour and multi-day
viewers. The two lines sat on top of each other. On inspection, people had been sorted by the pages
they looked at rather than by what they bought, so anyone who viewed both products was counted in
both groups, and since day tours are around 80 in 100 sales, most bookings in the multi-day group
were day tour bookings. The chart proves nothing in either direction. It was named on a slide as one
to stop quoting.

**Root cause.** Product-tagged sales data does not exist, so page views were used as a proxy for
product intent. The proxy was adopted without asking what result the method would produce if the
hypothesis were false. Two identical lines are what that method returns either way.

**Would have caught it.** Before building any comparison, asking what the chart would look like if
the hypothesis were wrong. If the answer is "the same", the method cannot test it.

**Cost.** Low in absolute terms; the error was caught before it drove a recommendation. Higher in
credibility, because it was caught after being charted rather than before, and it sat inside a deck
that made a strong claim about product differences.

---

## F3 The initiatives tracker forked into two sheet sets and both were kept

**Date.** 08/2026 to 09/2026

**What happened.** The tracking workbook contains two complete sheet sets: `Initiatives`, `Values`,
`Initiatives Original`, `value`, `RICE methodology`, and the same five again suffixed `(1)`. They
have diverged. The `(1)` set has 30 rows to the original's 26, adds two research initiatives and the
design system, and replaces four columns with a different four. Neither is marked as canonical.

**Root cause.** A shared workbook was restructured by duplicating sheets rather than versioning the
file, and the superseded set was left in place rather than deleted, presumably to avoid losing
anything.

**Would have caught it.** A file naming convention with a version suffix, and a rule that
restructuring produces a new file rather than new sheets. Also a check on delivery: if a workbook
goes out with two sheets that could both answer the same question, it is not finished.

**Cost.** Small so far, but the failure mode is silent. Anyone reading the older set gets a backlog
missing four initiatives, including both research commissions and the design system.

---

## F4 Placeholder effort estimates were entered as numbers and then used to rank

**Date.** 08/2026

**What happened.** Owned reviews carries an effort of 15 days. That figure is a Sunny Lemons
stand-in for "Large", which is how the source rated it, with no day count behind it and no dev
input. It now drives RICE rank 4. Separately, local specific content carries an effort recorded as
"Large / 2 to 3 days", which is internally contradictory, and it drives RICE rank 2. Nine further
initiatives have effort marked TBC and their ranks read "Pending".

**Root cause.** A scoring model that requires a number in every cell was applied to a backlog logged
at different levels of detail. The model's need for completeness overrode the honest answer, which
was that the effort was unknown. The provenance was recorded in a notes column, but the number
propagated into the rank and the rank is what gets quoted.

**Would have caught it.** Refusing to score any initiative with an unsourced effort, and letting the
gaps show as gaps. The nine TBCs prove this was possible; the two placeholders are where the
discipline slipped.

**Cost.** The top four RICE ranks include two resting on soft numbers. Any sequencing argument built
on them is exposed, and finding out in front of the client would be worse than finding out here.

---

## F5 Direct Packages 2.0 entered build with the test that was supposed to precede it unrun

**Date.** 06/2026 to 09/2026

**What happened.** The initiative carries an explicit requirement that user testing be run before
design, to confirm the root cause of the 60% drop at the accommodation step and the 60% drop at
personal details. The tracker records the test focus as "test before build". The initiative is in
build with a delivery date of 30/09/2026 and the test has not run. The accommodation diagnosis rests
on three participants who entered checkout to find accommodation information. The personal details
drop has no diagnosis at all.

**Root cause.** The test was recorded as a requirement inside an initiative rather than as a gate on
it. A requirement written in a column does not stop a build starting; a dependency does.

**Would have caught it.** Modelling test-before-build items as blocking dependencies on the tracker,
in the same field used for other dependencies, so that starting the build requires overriding
something visible.

**Cost.** Roughly 23 days of build effort split across two drop points, one of which is
well-diagnosed and one of which is not. If the personal details drop turns out to be a decision
pause rather than form friction, some of that effort is aimed at the wrong problem.

**Same pattern, live now.** The deposits baseline is a one-shot measurement: how far ahead multi-day
is booked today, how many reach basket, how many pay. Deposits delivery is 01/10/2026 and once it
ships the before-state cannot be recovered. This is the same class of failure, currently forming.

---

## F6 A contract carried three conflicting dates for over a year without being reconciled

**Date.** 08/2025 to 09/2026

**What happened.** The SOW header reads January 06 2025, the timeline reads commencement January 6
2026, and the signature block reads 04 August 2025. The discrepancy went unnoticed until the repo
was set up in September 2026. The explanation turned out to be simple: two engagements, with the
signature belonging to the earlier Direct Packages project and the header being a typo.

**Root cause.** Two engagements were documented in a way that did not distinguish them, and the
governing document was read for scope rather than checked for internal consistency. Nothing prompted
a re-read after signature.

**Would have caught it.** Extracting dates, milestones and acceptance criteria into a working
summary at signature, which forces every date to be read once deliberately. That is what
`engagement.md` now does, and it caught it in an afternoon.

**Cost.** Near zero in practice, but the exposure was real. The renewal conversation depends on the
end date, and an unresolved commencement date is an unhelpful thing to discover during a renewal
negotiation rather than nine months before one.

---

## F7 The research record cannot be reconstructed from the files

**Date.** Surfaced 07/09/2026, accumulated across the programme.

**What happened.** Three different sample sizes for Segment A were in active use across the deck,
the participant table and the working files, each defensible in isolation because each counted a
different thing. Maggie had been counted twice, her `.docx` and her markdown transcript being the
same session and the same Grain recording. Six markdown transcripts and one unnamed participant sat
outside the participant table. Segment C, six interviews cited in four separate repo files and in
delivered analysis, has no transcript, recording or participant record held anywhere in the project.

**Root cause.** The participant record was maintained as a by-product of each synthesis document
rather than as a register in its own right. Each write-up counted what it needed and moved on, so no
single artefact was ever responsible for being complete, and nothing reconciled them against the
raw store. Segment C went unmissed because it was cited from synthesis rather than from source.

**Would have caught it.** A single participant register, updated at the end of each fieldwork wave
before analysis starts, with one row per session and its segment label. Reconciling it against the
raw file store at each wave boundary would have caught both the duplicate and the missing wave when
they happened rather than four months later.

**Cost.** A sample size quoted in a delivered client deck that cannot be reconstructed. Six
interviews of client-funded research currently untraceable. Low cost to fix now, high cost if it had
surfaced in a client conversation instead.

**Two further instances found the same day, both from the same cause.** A completed 37 minute
interview with a repeat customer, recruited outside the standard channel from a Scotland travel
group post, appears in no synthesis and no register. It is the closest thing in the evidence base to
a direct Trusted Returner voice, and that persona's confidence rating was written on the stated
grounds that no such voice existed. Separately, an aborted 2 minute session was carried in the
record as a lost transcript when the participant had in fact been rescheduled and completed the next
day.

Both are the same failure in different directions: one real interview lost from the record, one
non-interview counted into it. A register maintained per wave would have caught each at the point it
happened.

---

## F8 A client data pack sat in the repo for two months while a context file asserted the opposite

**Date.** Data presented 08/07/2026. Divergence found 17/09/2026.

**What happened.** `business.md` recorded channel mix as "entirely unexamined here" and stated that
"nothing in the project speaks to it", naming it as probably the largest lever in the business and
an item to ask Alex for. The Spike Insight customer insights pack, presented to Rabbie's on
08/07/2026, contains the channel split by volume and by value, average booking value by market and
by channel, the repeat booking rate, cohort value and affluence profiling. Four gap markers in
`business.md` were false and had been for two months. `personas.md` separately stated that repeat
booking rate is not tracked, which was also false over the same period.

**Root cause.** New external analysis arrives into `analysis/` as a transcription task, and
transcription is treated as complete when the document is accurate. Nothing in the process requires
a new source to be reconciled against the standing context files it bears on. The gap markers in
`business.md` are written as prose assertions rather than as questions with an owner, so nothing
about them is self-invalidating when the answer arrives. The transcription was done well, which is
what made it easy to miss: the file was correct and the context around it was not.

**Would have caught it.** A reconciliation step at the end of transcription: before a new analysis
document is considered filed, check it against the gap markers in `business.md`, `personas.md` and
`assumptions.md`, and record what it closes, narrows or contradicts. Ten minutes at the point of
filing. The check belongs to the person filing the source, because they are the only one who has
read it.

**Cost.** Low in this instance, because nothing was delivered to the client on the false statement
and the divergence was found internally. The near miss is the point. `business.md` is explicitly a
read-before-recommending file, and a recommendation to investigate a channel mix that had already
been analysed would have cost credibility with the partner and with Rabbie's, who commissioned the
analysis and would recognise it immediately. It would also have looked like advising on something
the client already knew, which is the specific failure mode that damages an advisory relationship.

**Prevention recorded.** `business.md` now names the source, its date and what it closes, and its
"Where the numbers live" table carries a row for it. Whether the reconciliation step becomes a
standing habit is not yet settled and is the part that would actually prevent recurrence.

---

## F9 Platform-reported paid media figures were recorded as observed and carried two strategy memos

**Date.** Figures entered from the August 2026 review. Compromised by a tracking bug running
11/05/2026 to 22/09/2026, disclosed in the State of the Nation deck and found here 24/09/2026.

**What happened.** `business.md` recorded Google non-brand ROAS falling from 9.8 to 4.3 and Meta cost
per booking rising from £17 to £49 as `[observed]`. Both were used as load-bearing evidence in
`strategy/2026-09_late-booking-is-a-targeting-artefact.md` and
`strategy/2026-09_uk-versus-us-market-bet.md`, and repeated in both product data architecture case
drafts in `work/`. The Meta figure sits wholly inside the bug window and the Google figure partly.
Both overstate the decline by an unknown amount. Nothing affected has been delivered.

**Root cause.** Figures taken from a single reporting source were marked `[observed]` without
recording which system produced them. Platform-reported and GA4-reported metrics were not
distinguished, so nothing flagged that a steep deterioration on one basis had no counterpart on the
other. Rabbie's found the bug by exactly that comparison.

**Would have caught it.** Record the source system alongside any acquisition metric, platform or
GA4, and treat a sharp movement that appears on only one basis as unconfirmed until cross-checked.
The same reconciliation step F8 calls for, applied at the point a figure enters `business.md`.

**Cost.** Low so far, because the memos are internal and the direction probably holds: the corrected
slide still shows ROAS and cost per booking behind target. The exposure is magnitude. Both memos use
the size of the decline as persuasion, and it would have been quoted to a client who had already
diagnosed the bug.

**Prevention recorded.** `business.md` marks the affected lines as compromised. The two memos need
superseding, not editing.

---

## F10 <Your next one>

**Date.**

**What happened.**

**Root cause.**

**Would have caught it.**

**Cost.**

---

## Reviewing

`/lint-workspace` reads this file and flags live work matching the circumstances of a logged
failure. That is the point of the log: not a record of past pain, but a warning that fires while the
same conditions are forming again.

It also flags entries older than 90 days with no prevention recorded, since a failure whose control
was never put in place is a standing risk rather than history.

## Prompts for finding your own

Write these as they happen. Reconstructed months later, every failure looks like bad luck.

- What did you have to redo, and what would have prevented the first attempt being wrong?
- Where did a conversation happen that should have been a document?
- What did you assume was still true that had quietly changed?
- What did you know was a risk and not act on?
