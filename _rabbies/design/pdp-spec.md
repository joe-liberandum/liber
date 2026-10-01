# PDP spec

The tour page. The most contested surface on the site, because it is where qualification work is being moved to and where mobile conversion is being lost.

**Related.** `buy-box-spec.md`, `checkout-flow.md`, `patterns.md`, `accessibility-notes.md`.

---

## Mobile layout optimisation

**To do.** Owner Ecommerce. From Jun 2026. 4 days. **RICE rank 1, the highest on the backlog.**

Most paid social traffic is mobile. On mobile the things that help people decide (reviews, group size, map) sit too far down the page. High traffic, low bookings.

Reach 5, impact 3, confidence 0.75, effort 4 days. Effort and evidence both directly sourced from the original working document, which is unusual on this backlog and is why it ranks first.

**Caveat that must travel with this.** The inference is that low conversion on mobile paid social is a layout problem. It has not been ruled out that the traffic is poorly qualified. Check traffic quality signals before building. See A4 in `assumptions.md`.

**Module priority above the fold, from the research:**
1. Route map as lead visual
2. Reviews with attribution
3. Small group size as a headline claim
4. Price and availability

---

## Surface accommodation details on tour page

**In Design.** Owner Content. 15 days. RICE score 0.450.

Move accommodation type, price range and included attractions out of the booking flow and onto the multi-day PDP.

**Problem.** Customers enter the booking flow specifically to check accommodation information. Research-intent users are pulled into the funnel before they are ready, inflating false-entry abandonment. Three participants did exactly this.

**Scope.** Accommodation summary component for multi-day PDPs covering type, price range, what is and is not included, and an explanation of the process. Integration with the booking flow to avoid duplication. Mobile layout.

**Content requirements from research:**
- State plainly that Rabbie's books the accommodation. One participant did not know this until told in an interview. Another assumed it without the page saying so.
- Explain the concierge fee and what it covers. Currently confusing.
- Give the price range and honour it at booking.
- Say ensuite or not. Raised unprompted and repeatedly.
- Explain that reservation happens after booking, and how long confirmation takes.

**Dependency.** Accommodation content structure from the booking system. PDP layout capacity.

---

## Guide module

**In Design.** Owner Content. 10 days. RICE score 0.600.

A "Your Guide" or "Meet Our Guides" panel on every PDP with 2 to 3 guide profiles or stories.

**Scope.** Guide card component (photo, name, short bio, reviews mentioning the guide), placement within PDP layout, fallback state where the guide is not yet assigned.

**Blocked on content.** Guide content does not exist. Operations needs a spec of what the website requires so the right material gets gathered. A separate initiative exists for a collection mechanism, and it needs to be built alongside the test rather than after it.

**Evidence caveat.** All guide evidence is post-tour. Guide quality drives rebooking, and one day-tour customer attributed roughly 90% of experience quality to the guide. Whether a named guide moves a first-time booker is untested. See A6 in `assumptions.md`.

---

## Reviews

Not a standalone initiative on the tracker; delivered through Owned reviews under My New Account. Specified here because the defect is on the PDP.

**The problem is a trust break, not a gap.** Two Segment D participants independently lost confidence at the review section. One moved from interested to a firm no almost entirely on that basis. The section is a thin, unattributed Trustpilot feed. Photos are not tagged to specific tours, so a customer cannot tell whether a review photo is from the tour they are looking at.

**Photo attribution is bigger than it looks.** Backend tagging, review system changes, and display work. Flag the scope early.

**Confidence.** 95% on the problem. The fix is an assumption. See A7 in `assumptions.md`.

---

## Also specified for the PDP, not yet scoped

| Item | Source | Status |
|---|---|---|
| Show tour stops on PDP | Customers search Google for specific places. Also needed for compare and for paid search landing pages | Blocked on data structure check |
| Small group size as headline claim | Persona work, NOW tier | Not scoped |
| Driving-anxiety relief as explicit value proposition | Persona work, NOW tier | Not scoped |
| Route map as lead visual | Persona work, Interest phase | Folded into mobile layout |
| Save or share a tour | Booking-by-proxy behaviour. One participant texted links to her mum because there was no other way | Deferred to Q4 with wishlist |
| Related tours, recently viewed | Personalisation initiative, Algolia. 5.5 days | To do |
| Notify me when dates are added | Pre-released and cancelled tours initiative. 4 days | To do |
| Accessibility and mobility information | See `accessibility-notes.md` | Not scoped |

---

## Two products, one template

Day tour and multi-day PDPs currently share a template. They should not carry the same content weight. Accommodation, end dates, deposits and luggage are multi-day concerns. Pickup point, duration and departure time carry more weight on day tours.

No decision has been made on whether to diverge the templates. It is a live question for the design system work.
