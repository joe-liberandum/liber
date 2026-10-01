# Patterns

Recurring design positions established on this engagement. Apply by default. Say when you are departing from one and why.

This is not a component library. The component library does not exist yet, and its absence is initiative 17. This file is the reasoning that should end up encoded in it.

---

## Structural

**Two products, two journeys.** Day tours are itinerary fillers, booked after the trip exists. Multi-day tours are trip anchors, booked before flights and accommodation. Different timing, different content weight, different conversion logic. Any design that treats them as one funnel is wrong before it is drawn.

**Qualification belongs upstream.** Eligibility, accommodation, luggage, mobility and expectation setting go on the PDP, not in the booking flow. Late-stage surprises cause abandonment, and information-seeking users pulled into the funnel early inflate false-entry drop-off.

**Browse and book are different intents and need different doors.** Forcing a destination and a date before someone has decided anything filters out the flexible planner, who is a large share of the market.

**Three of the four personas decide before they reach the site.** The site's job is more often confirmation and reassurance than persuasion. Design for someone arriving with a shortlist, not someone arriving blank.

---

## Content and copy

**Say the thing plainly.** The site assumes prior brand knowledge and a person in the room. A large and growing share of traffic is first-time. Every proposition claim needs to work cold.

**Exclusions must not read as absences.** "Excludes accommodation" reads as a flat exclusion on tours where accommodation is available to add. One participant mentally rejected a tour on that basis before the moderator corrected her. State what is available, then what is not included in the price.

**Labels that have been misread, and should not be reused:**
- "Age rating: 5 years plus" confused two participants
- "B Corp" confused three participants
- "ABTOT" confused one
- "2 to 16" on private tours confuses party-size expectations
- Booking reference in small grey text was missed by two participants

Credibility badges are not self-explanatory, and this matters more as AI overviews surface badges without context.

**UK and US need different copy.** UK customers know Scotland, care more about price, book later, and trust ABTA and ATOL. The site addresses them as first-time visitors to the country.

---

## Trust

**Only two genuine differentiators exist.** Driver-guides, and depth of service on logistics and accommodation. Small group size, no driving, and flexible commitment are category parity. Do not claim them as differentiators, though small group size is still worth stating plainly as a fact.

**Attribution beats volume in reviews.** A thin unattributed feed actively breaks trust rather than failing to build it. Photos untagged to tours weaken the section further. Two participants lost confidence here; one moved to a firm no.

**Trustpilot is the wrong proof in some contexts.** Private tours needs bespoke testimonials from real private-tour customers.

**Confirmation needs to feel like something happened.** Moving too fast from payment to booked left older participants unsure the booking was real. A deliberate delay was added and validated positively. Speed is not always the goal.

---

## Anti-patterns

**Over-engineering a response to small feedback volumes.** Rabbie's tendency. Recommend the cheap reversible fix until volume justifies a designed feature. Best-performing existing marketing pages are product-first and focused; over-complicated pages are a documented failure mode.

**Building outside the component library.** Custom builds proliferating outside the library is a governance problem, not a technical one. Log it when you see it.

**The stitched-together itinerary.** The competitor anti-pattern. Multi-day continuity, same guide and same group, is the differentiating claim against it.

**Over-promising in itineraries.** A tour sold as "fishing villages" plural visited one fishing village and an inland village. A stop presented as included was optional on the day. Tolerated, but noticed.

**Custom-building every campaign page.** Without agreed story structures and page-type definitions, every campaign is built from scratch. This is why the landing page template work matters more than its rank suggests.

---

## Behaviour to design for, observed

| Behaviour | Design implication |
|---|---|
| Booking by proxy: a friend shortlists and emails links, recipient books from the shortlist | Save, share, send-to-a-friend on the PDP. Persuasion surfaces are bypassed entirely for this path |
| Manual comparison with spreadsheets, tabs, hand-drawn checklists | Compare, recently viewed, persistent passengers and dates |
| Back-to-back trip planning by counting days | End dates on the calendar, tour stops on cards |
| Group organiser books and is repaid | Shared booking view, currency choice matters more than travel party location |
| Repeated return to the homepage over weeks | Landing pages that serve return-and-research, not just arrive-and-buy |
| Backing out of the flow to discuss with a partner, then returning | Save state. The drop is not always a failure |
| Currency drives who books | A UK participant booked so the transaction stayed in Sterling. IP-based currency serving broke this for another customer |

---

## Prioritisation defaults

**RICE for ranking, judgement for sequencing.** State RICE inputs, not just the score. The methodology sheet says it directly: a planning input, not a substitute for judgement about dependencies or work already in build.

**Confidence below 0.6 with effort TBC means not ready to scope.** Nine initiatives currently sit there.

**Cheap and evidenced beats expensive and assumed.** Mobile PDP at 4 days and local copy at 2.5 days outrank everything else on the backlog and sit near the bottom of the delivery order.

---

## Visual and brand

Liberandum palette for deliverables: PINK `#D02E5E`, NAVY `#123C64`. Open typographic layout, whitespace and hairline dividers, avoid card-heavy designs.

This governs Sunny Lemons output, not the Rabbie's site itself. Rabbie's brand system is theirs.
