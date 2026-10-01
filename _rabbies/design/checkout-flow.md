# Checkout flow

The booking flow, both product tracks. What it does now, where it loses people, and what is changing.

**Status.** Direct Packages 2.0 in build. Owner Tech. Jun to Sep 2026.
**Figma.** Direct Package 2.0.
**Related.** `buy-box-spec.md` (entry point), `booking-form-spec.md` (passenger details), `pdp-spec.md` (the qualification work being moved upstream).

---

## Two flows, not one

This is the most important thing on the page. Day tours and multi-day tours are structurally different products and their flows behave differently. Never write a checkout recommendation that treats them as one funnel.

| | Day tour | Multi-day tour |
|---|---|---|
| Share of sales | Roughly 80 in 100 | Roughly 20 in 100 |
| Reach basket (Edinburgh) | 14 in 100 viewers | 13 in 100 viewers |
| Of those, pay | 38 in 100 | 13 in 100 |
| Accommodation step | Not present | Present, and the main drop point |
| Purchase framing | Itinerary filler, booked after the trip exists | Trip anchor, booked before flights and accommodation |

Interest is near identical. Completion is not. Multi-day reaches the basket as often as day tours and then loses three times as many people at the last step.

**Read this carefully.** That is not a marketing problem. It is doubt about a large purchase, and it belongs to the website work. Basket data is Edinburgh tours only with no date range on the export. Directionally clear, but re-pull before quoting outside the business.

---

## Multi-day flow as it stands

1. **Buy Box on PDP.** Passenger count and date. No price shown before selection. See `buy-box-spec.md`.
2. **Accommodation step.** Choose whether Rabbie's books accommodation or the customer arranges their own. Approved partner accommodation. Concierge fee applies.
3. **Passenger details.** See `booking-form-spec.md`.
4. **Review and pay.** Cost breakdown including the accommodation booking fee.
5. **Confirmation.** Booking reference, dates, luggage information, manage booking link.

### Where it loses people

**60% drop at the accommodation step.** The current diagnosis is that the step is doing qualification and expectation-setting work that belongs on the PDP. Customers are entering the booking flow specifically to find out what accommodation involves, which pulls research-intent users into the funnel before they are ready to book and inflates false-entry abandonment. Three participants did exactly that.

**60% drop at personal details.** Root cause not established. One participant said she would back out at payment rather than at details, describing the details step as feeling safe because Rabbie's already knowing her name was low risk. That is one voice and it points the other way.

**Both figures need user testing before design.** The tracker requires this and it is the right sequencing. See A5 in `assumptions.md`: the inference from "three people entered checkout for accommodation information" to "the 60% are those people" is not established.

---

## Known defects and friction, evidenced

| Issue | Evidence | Status |
|---|---|---|
| Accommodation intent unclear on entry | One participant assumed Rabbie's booked accommodation without the page saying so. Another did not know Rabbie's booked hotels at all until told in interview | Moving to PDP |
| Accommodation fee not explained | Participant confused about what the concierge fee covered. "How much am I paying for them to make the call to the hotel versus me" | Review-and-pay detail improved, not yet validated |
| No hand-holding into the accommodation decision | Participant said people might need to be told a decision is coming before the step lands | Open |
| Booking reference too small and grey on confirmation | Two participants independently failed to see it. One re-checked her email to confirm the booking was real | Design change made, validated positively in a later session |
| No emergency contact on confirmation | Participant wanted a number to call if someone breaks a leg. She prints the confirmation | Open. Cheap fix |
| Tour end dates not shown at date selection | Customers manually count days. One emailed to check whether two tours fit back to back | Buy Box work, 1.5 days |
| Currency served by IP, not by customer | A UK customer received one receipt in dollars and one in pounds | Architectural. Flagged to Rabbie's, not a design fix |
| Confirmation-to-booked feels too fast | Older participants unsure the booking had completed. A deliberate delay was introduced to make the process feel like it is happening | Shipped, validated positively |

---

## What is changing in Direct Packages 2.0

- Accommodation step refinement, component and copy, based on test results
- Personal details form review
- Booking progress indicator
- Summary panel
- Deposit messaging, once Deposits lands

Sequencing constraint: user testing before design, to confirm root cause of both 60% drops.

---

## Deposits

**In Design.** Owner Ecommerce. Jul to Oct 2026. Scoped separately by Stuart. Delivery projected at five to six weeks from the August deck.

A deposit option on every multi-day tour. Deposit figure surfaces after date and passenger selection and updates dynamically. Touches PLP, PDP and booking flow. Multi-day only.

**Time-critical action.** Record where multi-day booking sits today before launch: how far ahead people book, how many reach basket, how many pay. Once deposits are live the before-state cannot be recovered.

**Evidence caveat.** One participant described reserve-now-pay-later elsewhere as excellent. Another compared Rabbie's unfavourably with the 20% deposit pattern used by other travel bookings. No abandoners have been interviewed, so nothing confirms deposits recover abandoned bookings specifically. See A8 in `assumptions.md`, confidence low.

---

## Open questions

- Is the personal details drop a form problem, a price-reveal problem, or a decision-pause problem? Not answered.
- Does the accommodation step drop reflect information need, price, or genuine disqualification?
- Does a booking summary page before payment reduce the last-step drop? Recommended in the persona work, never scoped.
- Cancellation policy is not surfaced prominently in the flow. Recommended, not scoped.
