# Frontend: patch, strangle, or rebuild

**Date.** 07/09/2026
**For.** Yourself.
**Status.** Draft. This is an options paper. There is no recommendation yet, and that is the point.

## Recommendation

None. There is no evidenced recommendation to make, and the question should not go to the Rabbie's C-suite until there is.

The prerequisite is a comparison that does not exist: scope individual initiative effort against the current frontend versus a rebuilt one. Until that comparison is done, any recommendation is an aesthetic preference with a business case attached after the fact.

## Why

Every effort figure on the tracker, and therefore every RICE rank and the whole 2026 sequencing, assumes the current frontend can carry the work. Nothing supports that assumption. It is being carried rather than closed.

Nine initiatives have effort marked TBC, including three of the four largest: landing page templates, Buy Box and Deposits. Those nine are exactly where a frontend constraint would first show up as inflated estimates. The information needed to answer the rebuild question is the same information needed to finish the tracker.

The design system makes the cost visible. Components are built per initiative, patterns are rebuilt each time, and templates drift. Templates for five page types are in scope across the navigation, IA and landing page work with no shared component definition. Custom builds proliferating outside the component library is a governance failure as much as a technical one, and it compounds weekly.

## What this rests on

- A10: the current frontend can carry the backlog without a rebuild. Confidence low. Rests on nothing.
- A11: the backlog adds up to the 1% conversion target. If the target is unreachable through incremental work, the rebuild case changes entirely.

## What would change this

Effort estimates for IA restructure, landing page templates and the design system coming back materially higher against the current frontend than a rebuild would cost to amortise over the remaining contract and beyond.

## Options considered and rejected

**Patch and continue.** Not rejected, currently in force by default. Lowest immediate cost, and the drift cost is invisible until a template count makes it visible. The risk is that it is being chosen by inertia rather than by decision.

**Full rebuild.** Rejected for now. No evidence base, large disruption to work in build, and it would stall the navigation and Direct Packages work mid-flight.

**Strangler pattern, incremental replacement.** Identified as the preferred middle path. Not recommended, because preferring it without the effort comparison is exactly the mistake this memo exists to avoid.

**Taking the question to the C-suite now.** Rejected. Asking for a decision without the comparison spends credibility and invites a decision made on instinct.

## Next

Scope three initiatives both ways as a sample: IA restructure, landing page templates, and the design system. Those three are the largest and the most template-dependent, so they carry the signal. That is a Sunny Lemons and Rabbie's dev joint exercise and it needs asking for.
