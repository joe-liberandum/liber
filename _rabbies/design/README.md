# Design

Design thinking, surface specs, and developer facing briefs.

## Index

| File | Covers |
|---|---|
| `patterns.md` | Recurring design positions and anti-patterns. **Read this first.** |
| `navigation-and-ia.md` | Nav redesign (in QA), IA restructure (in build), homepage entry point |
| `plp-and-filters.md` | Listing page, filter data blocker, tour stops, personalisation |
| `pdp-spec.md` | Tour page: mobile layout, accommodation surfacing, guide module, reviews |
| `buy-box-spec.md` | PDP booking widget: from price, booking options, end dates |
| `checkout-flow.md` | Booking flow, both product tracks, and Deposits |
| `booking-form-spec.md` | Passenger details step |
| `account-and-post-booking.md` | Account, owned reviews, referral, post-tour, pre-tour comms |
| `landing-pages.md` | Templates, late availability, private tours, local copy |
| `accessibility-notes.md` | Findings log and requirements. Not an audit; none exists |
| `test-variants/` | CRO test register and individual test definitions |

Initiative status, RICE scores and effort figures live in `../initiatives.md`. The beliefs these specs rest on live in `../assumptions.md`.

## Rules

- Every developer facing brief uses the ICE structure, in this order: **Intent**, **Context**, **Expectations**.
- State which persona and which journey phase the work serves. Awareness, Interest, Desire, Action, Return.
- State whether it applies to day tours, multi-day tours, or both. These are different products and most briefs apply to only one.
- Carry the evidence caveat with the recommendation. Nine initiatives have a named evidence gap; a spec that drops the caveat is worse than no spec.
- Prefer the cheap reversible fix. Do not design a feature where a content change would do, until volume justifies it.
- Note where the component library is being bypassed. That is a governance signal, not just a build detail.

## Live constraints

- The navigation redesign is live and post-launch CRO tests are queued. Coordinate with Salience so design work does not clash.
- PLP work is blocked on the tour data structure. Do not design filter changes before filter usage data exists.
- The guide module is blocked on content that operations has not been asked for yet.
- Nine initiatives carry `Effort (days): TBC`, including three of the largest. Any sequencing argument is provisional.
