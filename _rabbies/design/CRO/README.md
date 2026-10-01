# Test variants

CRO test register. One file per test, named `YYYY-MM_short-slug.md`.

**Ownership.** Liberandum runs testing in VWO. Sunny Lemons defines the hypothesis, the variant, and what would falsify it. Sarita is the CRO specialist. Do not write test mechanics here that belong to Liberandum; write the design intent and the decision the test should settle.

**File format.** Hypothesis, variant description, primary metric, what would falsify it, what decision it unblocks, status.

**Rule.** A test that cannot change a decision should not be run. If the build is going ahead either way, say so and skip the test.

---

## Register

Drawn from the `CRO test` and `CRO test focus` columns of the initiatives tracker. Dates are proposed windows, not scheduled.

### Test before build

These sit in front of a design decision. Running them late means testing something already built.

| Test focus | Initiative | Status |
|---|---|---|
| Accommodation step and personal details form | Direct packages 2.0 | **Overdue.** Initiative is in build. See the variant file |
| From price display and format | Buy Box | Not scheduled. Effort TBC |
| Booking option routing after availability check | Buy Box | Not scheduled. Effort TBC |
| Mobile PDP module order above the fold | Mobile PDP layout | Not scheduled. See the variant file |
| Page story structure and module order | Landing page templates | Not scheduled. Effort TBC |
| Late availability page layout and sort order | Late availability | Blocked on persona research |
| UK facing copy and trust signal placement | Local specific content | Not scheduled |

### Test after launch

| Test focus | Initiative | Status |
|---|---|---|
| Nav label set and category order | Navigation redesign | **Due now.** Nav shipped Aug 2026. See the variant file |
| Guide module presence and placement on PDP | Guide module | Blocked on guide content |
| Accommodation summary presence and depth on PDP | Surface accommodation | Follows build |
| Date range highlighting in calendar | End dates on calendar | Follows build |
| Passenger and date persistence across PDPs | Persist session | Follows build |
| Deposit messaging, full pay versus deposit | Deposits | Follows build |
| Owned review display on PDP | Owned reviews | Follows build |
| Related tours and recently viewed modules | Personalisation | Follows build |
| Notify me component on unavailable dates | Pre-released tours | Follows build |
| Referral prompt placement and wording | Referral mechanism | Marked not suitable for test in tracker, but focus recorded |

### Not suitable for test

IA restructure (validate via SEO and search metrics), PLP data structure (foundational, unlocks later tests), My New Account (infrastructure, test features later), Invite to tour (measure adoption instead), the two research initiatives, and the design system.

---

## Sequencing constraint

The navigation redesign changes category taxonomy and URL structure, and Salience is making SEO changes on the same surfaces. Do not run nav or landing page tests that clash with SEO work landing at the same time. Coordinate before scheduling.
