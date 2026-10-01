# RICE is a planning input, not the delivery sequence

**Date.** 07/09/2026
**For.** Yourself.
**Status.** Draft. Position established when the tracker was scored; stated on the RICE methodology sheet.

## Recommendation

Keep both orderings on the tracker and never collapse them. Quote the RICE rank, then say what sequencing says and why they differ. Use the divergence as the argument for pulling two cheap items forward, not for resequencing the two large ones already in build.

## Why

The tracker carries two independent priority columns and they disagree sharply.

Mobile PDP layout is delivery priority 12 and RICE rank 1. Local specific content is priority 14 and RICE rank 2. Both are cheap, 4 days and 2.5 days, high reach, and directly evidenced. Navigation redesign is priority 1 and RICE rank 6. Direct packages 2.0 is priority 2 and RICE rank 11. Both are in QA or build with real dependencies and cost 20.5 and 23 days.

That is not an argument to resequence nav or Direct Packages. It is an argument that two cheap, well-evidenced items are being under-served relative to what they would return.

The RICE methodology sheet says the constraint plainly: a consistent way to rank initiatives logged in different formats, and a planning input rather than a substitute for judgement about dependencies, sequencing, or work already in build.

## What this rests on

- A10: the current frontend can carry the backlog without a rebuild. Every effort figure, and therefore every rank, assumes this. Nothing supports it.
- A11: the backlog adds up to the 1% conversion target. No initiative carries a forecast contribution and nobody has modelled it.

## What would change this

Effort figures landing materially differently once the nine TBC items are scoped. Three of the four largest workstreams are among them: landing page templates, Buy Box and Deposits. Any total, any capacity plan and any RICE-based sequencing argument is provisional until they land.

Two ranks already rest on soft numbers. Local content ranks 2 on an effort recorded as "Large / 2 to 3 days", which is self-contradictory. Owned reviews ranks 4 on 15 days that is a Sunny Lemons placeholder for "Large", not a dev estimate.

## Options considered and rejected

**Presenting RICE as the roadmap.** Rejected. It would argue for stopping work already in build and would be ignored, correctly.

**Dropping RICE and sequencing on judgement alone.** Rejected. The scoring is what surfaced mobile PDP and local copy at all. Without it they stay at the bottom of a list nobody revisits.

**Rescoring to make the two orderings agree.** Rejected outright. That is fitting the model to the plan.

## Next

Get the nine TBC efforts scoped, starting with landing page templates, and confirm the two soft effort figures with dev. Until then, do not present a total as if it were complete.
