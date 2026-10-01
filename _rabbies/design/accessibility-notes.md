# Accessibility notes

What is known about accessibility on the Rabbie's site, and what is not.

**Honest position first.** No formal accessibility audit has been conducted on this engagement. WCAG conformance level is unknown and untested. Everything below comes from moderated sessions where accessibility surfaced incidentally, plus requirements attached to initiatives in flight.

This file should not be read as an audit. It is a findings log and a requirements list.

---

## The one substantial finding

**Mobility and life-stage information is missing from tour pages.**

A Segment D participant planning a trip to Ireland for a family of three, including her 85-year-old mother, spent a sustained part of her session failing to find mobility information on tour pages. She concluded she would have to phone.

Single case, but the stakes are high. Family decisions involving an older or disabled traveller stall entirely without this information, and phoning is a hard barrier for a customer in a different timezone with no live chat available.

**What is missing.** Walking distances per stop. Terrain. Time on foot versus on the vehicle. Vehicle accessibility. Step-free options. Whether a wheelchair or walker can be accommodated. Toilet stop frequency.

**Where it belongs.** The PDP, under the qualification-upstream principle. This is exactly the class of information that currently forces people into the booking flow or onto the phone.

**Status.** Not scoped. Not on the tracker. Should be folded into the accommodation and qualification content work on the PDP rather than raised as a separate initiative, since it needs the same content-gathering process from operations.

---

## Adjacent findings

**"Age rating: 5 years plus" is misread.** Two participants found it confusing. Recurring across sessions. It is doing eligibility work with a label borrowed from a different domain.

**Special requirements is a free-text field** in the booking form. It carries dietary and accessibility information into operations. Do not remove or shorten it in the form review without checking with operations first. See `booking-form-spec.md`.

**Support hours exclude North America.** One participant asked for live chat or WhatsApp with timezone-aware coverage, at 82% confidence in Segment D research. For a customer who cannot get accessibility information from the page, the fallback channel is closed during their waking hours.

**Older users need confirmation to feel confirmed.** Participants over roughly 65 were unsure a booking had completed because the flow moved too quickly from payment to booked. A deliberate delay was added and validated positively. Small booking-reference text in grey was missed by two participants, one of whom re-checked her email to be sure. Both are legibility and reassurance issues as much as accessibility ones.

**Printing the confirmation is a real behaviour.** One participant prints it and wanted an emergency contact number on it. Print stylesheets have not been checked.

---

## Requirements to carry into work in flight

| Workstream | Requirement | Status |
|---|---|---|
| Navigation redesign | Mobile accordion keyboard operable, focus visible, hover states have a non-hover equivalent | In scope, not verified |
| Buy Box | Calendar date-range highlighting must be conveyed by more than colour. Keyboard date selection | Not verified |
| Booking form | Correct input types and mobile keyboards. Autofill and browser autocomplete working. Error messages associated with fields | Not verified |
| Mobile PDP | Touch target sizes. Reflow at 320px. Text resize to 200% | Not verified |
| PDP guide module | Alt text on guide photos. Fallback state when no guide is assigned | In scope |
| Reviews | Photo alt text. Star ratings not conveyed by colour or shape alone | Not scoped |
| Design system | Contrast tokens defined once, at AA minimum, rather than per component | Enabler, not started |

---

## What should happen

1. **Fold mobility and terrain information into the PDP content spec.** It needs the same operations content-gathering as accommodation and guides, so it should ride with them rather than queue behind them.
2. **Run a WCAG 2.1 AA audit on the booking flow before Direct Packages 2.0 ships.** Redesigning a flow without knowing its current conformance means rebuilding the same defects.
3. **Define contrast and focus tokens inside the design system work**, not per initiative. Doing it per initiative is how the current drift happened.
4. **Add accessibility screening to research recruitment.** Every accessibility finding here is incidental. Nobody with a disability has been deliberately recruited into any session on this engagement.

Point 4 is the real gap. The rest is remediable; a research programme that never recruits disabled participants will keep producing incidental findings only.

---

## Not known

- Current WCAG conformance level, anywhere on the site
- Screen reader behaviour through the booking flow
- Whether the site has ever been audited by anyone
- Whether Rabbie's has a public accessibility statement
- What proportion of customers have accessibility needs. Given the age skew in the booker sample, plausibly significant and entirely unmeasured
