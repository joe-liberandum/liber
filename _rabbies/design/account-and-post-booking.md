# Account and post-booking

Everything after payment, plus the account infrastructure that several other initiatives depend on.

**Owner.** Tech and Content. **Depends on Deposits completing.**

---

## My New Account

**To do.** From Aug 2026. 25 days for the core build. RICE rank 9.

Auth, shortlisting and favouriting of tours, and transfer of existing manage-booking features into the new account.

**Problem.** Account infrastructure is fragmented and carries a known security risk. Planning and comparing multiple tours, and managing a booking after purchase, is manual and disconnected.

**Evidence.** Meticulous Planners and Purposeful Adventurers cite tour planning as a pain point and post-booking management as confusing. 52% of multi-day buyers view 2 or more tours before purchasing. Back-to-back trip planning is done entirely by hand. One participant kept a giant trip budget spreadsheet and recorded her booking reference and currency conversion into it manually.

**Deferred once already.** Pushed to the Q3 mid-year review on dev capacity, with Deposits prioritised by the Rabbie's board. A capacity decision, not a merit one. Notify-me and email-me-this-tour are worth proposing as small items sized to fit alongside Deposits.

---

## Owned reviews

**To do.** 15 days. **RICE rank 4.** Highest confidence on the entire backlog at 0.95.

Post-tour, prompt the customer to leave a review through their account, building a catalogue of owned reviews displayed on the relevant PDPs.

### The model as defined

- Tokenised magic link
- Guide-prompted QR scan at the peak emotional moment during the tour
- Mandatory publication of negative reviews
- Referral prompt at confirmation

### Why this ranks so high

Segment D rated moving beyond the thin Trustpilot feed to verified, attributed post-tour reviews as the single clearest conversion blocker identified in that research. Two participants independently lost trust at the review section.

### Two cautions

**The 95% is confidence in the problem, not the fix.** The evidence establishes that the current reviews section breaks trust. It does not establish that owned reviews are the fix rather than volume, recency, or photo attribution. See A7 in `assumptions.md`.

**The 15-day effort is a Sunny Lemons placeholder.** Segment D rated the item "Large" with no day count. 15 days is a Large-equivalent stand-in, not a dev estimate. Both the effort and the rank need confirming with dev before this is used to argue sequencing.

### Related

Photo attribution to specific tours is a separate, larger job: backend tagging, review system changes, display work. Flag the scope early.

---

## Referral mechanism

**To do.** 2.5 days. RICE rank 7.

Referral reward and credits in the account.

Trusted Returners are the primary acquisition channel for new high-intent visitors, and there is currently zero infrastructure to track or reward that advocacy. One participant proposed referral and sign-up incentives unprompted.

Cheap, and the only initiative that addresses the Trusted Returner directly. Note that Trusted Returner sits at 65% persona confidence, the lowest of the four, and was not directly represented in any new-visitor sample by design. Treat this as hypothesis generating.

---

## Post-tour email and loyalty sequence

**To do.** 2.5 days. RICE rank 5.

No structured post-tour communication exists, so the moment when rebooking intent and review-writing intent are both highest is currently wasted.

**Sequence as defined in the persona work:** review prompt, related tour suggestions, referral prompt. Also used to seed awareness of new routes and seasonal availability.

Guides are the primary driver of rebooking. Multi-day discoverability is weak even among satisfied day-tour customers: one day-tour booker, primed to rebook, did not know the multi-day catalogue existed. Post-tour cross-sell is the obvious lever and nothing currently pulls it.

Tested via CRM, not on site.

---

## Invite to tour

**To do. Effort TBC. Confidence 0.3, the lowest on the backlog.**

Invite a friend to a booked tour so they can see full booking details.

**Evidence gap.** Not directly tested. Inferred from one participant acting as coordinator, booking for a group of friends who pay him back.

**Adjacent and stronger.** Booking by proxy is a real decision path: a trusted friend pre-shortlists and emails links, and the recipient books from that shortlist, bypassing reviews and most persuasion surfaces. That points at a save, share, or send-to-a-friend mechanic on the PDP rather than a post-booking invite. The two should be scoped together.

Not suitable for A/B test. Measure adoption instead, after the share-tour test.

---

## Pre-tour communication

Specified in the persona work. Not currently a tracker initiative. Cheap and repeatedly evidenced.

| Item | Evidence |
|---|---|
| Automated interim accommodation communication within days of booking | One customer heard nothing for several weeks after booking and went looking through her email |
| Honour the accommodation price range stated at booking | Participant reported a price surprise |
| Standardise and proactively send pre-trip logistics | Luggage information was described as helpful when found, but it had to be found |
| Basic post-booking account view | Raised unprompted as the reason the post-booking relationship feels thin |
| Emergency contact on the confirmation | Participant prints the confirmation and wanted a number to call if someone is injured |

The confirmation page is the last owned surface before a silence of weeks or months. It currently carries a booking reference (previously too small and grey, now improved), dates, luggage information and a manage-booking link.

---

## Pre-released, cancelled and new-date tours

**To do.** 4 days. RICE rank 8.

Customers interested in a tour with no dates yet, or a tour that was cancelled, have no way to register interest. They check back manually or book with a competitor.

Named explicitly by one participant. Notify-me component on unavailable dates. Test after launch.

Plugs pipeline leakage and captures high-intent demand before it leaves.
