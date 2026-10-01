# Buy Box spec

The PDP booking widget. Date, passengers, price, and the route into the booking flow.

**Status.** In Design. Owner Ecommerce. From Jul 2026. **Effort TBC, RICE pending.**
**Scoping doc.** Google Doc, Buy Box redesign.
**Related.** `checkout-flow.md`, `pdp-spec.md`.

---

## Problem

The Buy Box does not show pricing per option upfront, so customers cannot see cost before selecting passengers, dates and booking options. Every question the customer has about price and availability is answered on the far side of a commitment.

---

## Three sub-tasks

### Add from price
Show a from-price before selection. **Effort TBC. Confidence 0.5.**

### Add booking options
After passengers and dates are chosen and availability is checked, present routes suited to how the customer wants to book, each leading into its own simplified journey. Currently one generic path. **Effort TBC. Confidence 0.5.**

### Add end dates on calendar
When a start date is selected, highlight the full date range the tour covers so the end date is visible at a glance. **1.5 days. Confidence 0.75. RICE rank 3.**

Cheapest well-evidenced item on the backlog. Customers manually count days to plan back-to-back trips. One customer emailed to check whether two tours fit together. Another built her own checklist to compare stops.

---

## Evidence position, stated plainly

**No dedicated Buy Box usability study has ever been run.** Two of the three sub-tasks sit at 0.5 confidence and their personas are inferred from booking-flow behaviour rather than tested against the Buy Box itself.

What exists is related signal: booking-flow walkthroughs where customers actively sought clearer pricing and availability during checkout, and one session showing confusion when a multi-day package bundled attraction tickets with no clear route to see what was included.

End dates is the exception. That has direct evidence and a real day estimate.

Do not present the Buy Box work as evidence-led. It is a reasonable design bet with one evidenced component inside it. See A-series entries in `assumptions.md`.

---

## Trigger and dependency

Deposit messaging must be updated as part of the Deposits scope. That is the stated opening for the wider Buy Box changes, which come from the original Direct Packages scope: from price, full dates in the calendar, booking types.

If Deposits does not proceed, the Buy Box work loses its trigger and needs its own justification.

**Deposit display requirement.** Deposit figure surfaces after date and passenger selection and updates dynamically with party size.

---

## Requirements

**Intent.** Let a customer see what a tour costs and what booking it involves before they commit to entering the booking flow.

**Context.** PDP, both day and multi-day. Multi-day carries the deposit and the accommodation implication; day tours do not. Mobile is the priority viewport, see `pdp-spec.md`.

**Expectations.**

- From-price format must be unambiguous about what it excludes, particularly accommodation on multi-day. See the "Excludes accommodation" problem in `patterns.md`.
- Date range highlighting must work on mobile calendar, which is where most paid social traffic lands.
- Booking option routing must not add a step for customers who want the default path.
- Test before build on from price and booking options, per the tracker. Both are at 0.5 confidence.

---

## Open questions

- What are the actual booking options? The tracker describes the mechanism, not the set.
- Does a from-price help or hurt when accommodation is excluded from it?
- Effort is TBC on two of three sub-tasks, so this cannot be sequenced against anything yet.
