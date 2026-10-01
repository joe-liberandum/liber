# Strategy

Decision memos. One decision per file, using the memo template.

**Audience.** Internal by default. These are written for you, not for the client. They contain commercial judgement, things not yet said to Rabbie's or Liberandum, and honest assessments of where the evidence is thin. Check the **For** line before reusing anything from here in a client deliverable.

**Naming.** `YYYY-MM_short-slug.md`, dated by when the memo was written, not when the decision was taken. The decision date goes in the Status line.

**Rule.** A memo is superseded, never edited. When a decision changes, write a new memo and set the old one's Status to `Superseded by <file>`. The reasoning that was wrong is worth keeping.

**The `What this rests on` section is the point of the format.** It names the assumptions from `../assumptions.md` by number. When an assumption is falsified, grep this folder for its number to find every memo that needs revisiting.

---

## Index

### Decisions taken

| Memo | Decision |
|---|---|
| `2026-09_two-track-product-model.md` | Day tours and multi-day are separate funnels |
| `2026-09_personas-as-shared-frame.md` | Four personas across all three agencies, sequenced by confidence |
| `2026-09_late-booking-is-a-targeting-artefact.md` | Booking data reflects spend timing, not customer decision timing |
| `2026-09_qualification-moves-upstream.md` | Eligibility and accommodation content belongs on the PDP |
| `2026-09_rice-is-an-input-not-the-sequence.md` | Keep both orderings, never collapse them |
| `2026-09_q3-q4-deferrals.md` | Five initiatives deferred, with the reasoning |
| `2026-09_owned-reviews-over-trustpilot.md` | Owned attributed reviews as the primary trust surface |

### Open questions

| Memo | Question |
|---|---|
| `2026-09_frontend-options.md` | Patch, strangle, or rebuild. No recommendation yet, deliberately |
| `2026-09_commissioning-non-booker-research.md` | Commission abandoner research as an additional service |
| `2026-09_mid-length-duration-gap.md` | 3 to 4 day tours. Rabbie's decision, needs an owner |
| `2026-09_uk-versus-us-market-bet.md` | Whether US decline justifies the deferrals made on it |

---

## Assumption coverage

Which memos depend on which assumptions. Update when you add a memo.

| Assumption | Memos depending on it |
|---|---|
| A1 personas describe the market | two-track, personas, owned-reviews, non-booker-research, duration-gap, uk-vs-us |
| A2 late booking is a targeting artefact | late-booking |
| A3 92% drop-off is addressable | late-booking, qualification-upstream, non-booker-research |
| A5 qualification upstream reduces abandonment | qualification-upstream |
| A7 owned reviews fix the trust break | owned-reviews |
| A8 deposits recover hesitant bookers | non-booker-research |
| A9 duration gap is real demand | duration-gap |
| A10 current frontend carries the backlog | rice-is-an-input, frontend-options |
| A11 backlog adds to 1% | rice-is-an-input, q3-q4-deferrals, frontend-options |
| A12 UK growth over US recovery | q3-q4-deferrals, uk-vs-us |

**A1 carries six memos.** If abandoner research breaks it, six decisions need revisiting at once. That concentration is itself an argument for the research commission.

**A4 and A6 carry no memos.** Both are live design assumptions (mobile traffic quality, guide visibility pre-booking) that have not yet been raised to a decision. Worth noticing.
