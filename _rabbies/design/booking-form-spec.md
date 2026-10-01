# Booking form spec

The passenger details step. Part of the checkout flow, specified separately because it is one of the two 60% drop points and is being reviewed in Direct Packages 2.0.

**Status.** In build as part of Direct Packages 2.0.
**Related.** `checkout-flow.md`, `accessibility-notes.md`.

---

## Current behaviour

Collected at this step:

- Lead booker details (the person booking)
- Additional passenger names
- Special requirements, free text
- Travelling with friends, so separately booked parties can be kept together
- Marketing opt-in for travel tips

### Change already made

Full details for every passenger are no longer required. Only the lead booker gives full details; additional passengers need a name. A participant confirmed this as a positive change during a walkthrough.

---

## Evidence

**The 60% drop is not explained.** The step follows accommodation selection on multi-day, so the population arriving here has already survived one large drop. No test has isolated whether the loss is form burden, price anticipation, or a natural pause point.

**One counter-signal.** A participant said she would back out at payment rather than at details, describing the details step as low risk because she did not mind Rabbie's knowing her name. She also described reaching this point several times and backing out to discuss with her husband before booking. That is a decision-pause pattern, not a form-friction pattern, and it argues against a pure form-simplification fix.

**Group booking is real.** One participant books on behalf of a group who pay him back. Another books so the transaction stays in her own currency. The "travelling with friends" field partly serves this, but there is no shared view of the booking for the other travellers. See Invite to tour in `initiatives.md`, confidence 0.3.

---

## Requirements for the review

**Intent.** Establish why the personal details step loses 60% of the people who reach it, then reduce that loss without removing information operations needs.

**Context.** Multi-day flow only for the drop-off figure. Day tours use the same form with no accommodation step before it, so the arriving population is different and the figures are not comparable. Marketing opt-in and special requirements are both operationally requested fields, not design additions.

**Expectations.**

- User testing before design, per the tracker. Do not redesign on the assumption of form friction.
- Any field removed must be checked against operations, particularly special requirements, which carries accessibility and dietary information.
- Progress indicator is in scope for the wider flow and should reach this step.
- Autofill and browser autocomplete behaviour must work. Not currently verified.
- Mobile keyboard types must match field types. Not currently verified.

---

## Open questions

- Is the drop concentrated on a specific field, or spread across the step? Field-level instrumentation does not exist.
- Does the form differ for day tours, and does the day tour version drop at a comparable rate? If not, the accommodation step is implicated rather than the form.
- Should the marketing opt-in sit here at all, or move to confirmation where commitment is already made?
