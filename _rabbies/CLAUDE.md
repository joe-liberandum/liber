# Rabbie's

Working repo for the Sunny Lemons engagement on Rabbie's Tours. Read this file, `engagement.md`, and `research/findings.md` before starting any new piece of work.

---

## Who is who

| Party | Role |
|---|---|
| Joe Collingwood, Sunny Lemons | UX and CRO strategist. Named author on deliverables. |
| Sunny Lemons | Research, UX strategy, design, delivery oversight. The agency credit on outputs. |
| Liberandum | CRO and analytics partner, and the contracting client. Kev (Director), Keating (Account Manager), Sarita (CRO Specialist). |
| Rabbie's Tours | The end client. Alex (CGO), Michelle (Marketing Director). |
| Salience | SEO and paid media agency. Coordinate with them, do not duplicate their work. |

Rabbie's is a Scottish small group tour operator running day tours and multi-day tours across the UK and Europe. Contractually, Sunny Lemons is engaged by Liberandum, and deliverables are for Rabbie's benefit.

**Two engagements, not one.** A discrete Direct Packages booking flow and user testing project ran in 2025. The full year UX and research engagement runs from January 2026 and was secured off the back of it. Direct Packages Phase 1 shipped under the earlier contract, Phase 2 sits under the current one. Be clear which engagement a decision was made under when referencing that history.

---

## The commercial problem, in one paragraph

Around 92% of visitors drop off in the interest and desire phases. The site was built for returning visitors, but a large and growing share of traffic is first time. Booking data shows late purchases, but that pattern reflects a late targeting strategy rather than a late deciding customer. Work is organised around four validated personas and a two track journey model that separates day tours from multi-day tours.

---

## Folder map

| Folder | What goes in it | Rules |
|---|---|---|
| `analysis/` | Data work. GA4 pulls, backlog exports, booking window models, spreadsheets, scratch calculations. | Internal. Not client facing. Keep the raw input alongside the output so numbers can be re-derived. |
| `research/` | `findings.md`, `plan.md`, `SOURCES.md`. Rolling synthesis, not raw data. | Raw transcripts live outside this repo. `SOURCES.md` points to them. |
| `design/` | Wireframe briefs, IA proposals, ICE briefs for developers, component and pattern notes. | Every developer facing brief uses the ICE structure. See below. |
| `work/` | In progress drafts, decks being built, generation scripts. | Anything here is unfinished. Do not treat as agreed. |
| `delivered/` | What has actually gone to the client. Dated and versioned. | Append only. Never edit a delivered file in place. New version, new file, with a version note. |
| `strategy/` | Decision memos, one per file. Internal by default. | A memo is superseded, never edited. Each names the assumptions it rests on by number. |
| `engagement.md` | Scope, dates, success measures, exclusions. | The contract boundary. Check work against it before proposing anything. |
| `assumptions.md` | The load-bearing beliefs that are not established facts. | Attack this in strategic sessions. Move an assumption to `CLAUDE.md` when it becomes established. |
| `decisions.md` | Choices made, with reasoning and the evidence that would reverse them. | Append only. Supersede with a new dated entry, never rewrite. |
| `failures.md` | What went wrong, why, and what would have caught it. | Append only. Never record a person as the cause. |
| `initiatives.md` | The 2026 backlog: status, RICE, evidence gaps. | Summary of the tracker. The workbook wins where they disagree. |
| `personas.md` | The four personas, with evidence marked and dissent recorded. Also holds roles, which are a separate class. | Do not create a fifth persona. Sequence by confidence. Roles are not personas, see below. |
| `business.md` | How Rabbie's makes money, and what is not known about it. | Read before any CRO or UX recommendation. The gaps are the point. |
| `notes.md` | Append only running log. Newest at the bottom. | Every session that produces or changes something adds a dated entry. |

---

## Rules for every session

1. Read `engagement.md` and `research/findings.md` first. Do not start from memory.
2. Ask clarifying questions before producing anything substantial. Flag assumptions up front rather than burying them.
3. Append a dated entry to `notes.md` when work is produced or a decision is made. Newest at the bottom. Do not edit or reorder earlier entries.
4. Corrections are made transparently. Add a version note explaining what changed and why. Never silently overwrite.
5. If a factual error is found, cascade the fix across every affected deliverable and say which ones were touched.
6. If something is out of scope per `engagement.md`, say so before doing it.

---

## House style

These are non negotiable on anything that leaves the repo.

- **Plain language.** Target a reading age accessible to internal Rabbie's teams without interpretation. No buzzwords. No consultant filler.
- **No em dashes. No en dashes.** Use commas, full stops, or colons. Write ranges as "3 to 4", not with a dash.
- **BLUF on every deck.** The answer comes before the evidence.
- **Short sentences.** Cut any sentence that survives being cut.
- **Participant references use initials and a segment label only.** Never full names in research documents or slides.
- **Caveats appear on the slide itself**, not only in speaker notes.
- **Speaker notes on every slide.**
- **Joe's voice is preserved** when adapting his drafts. Keep his structure, informal register, and first person framing. Do not smooth it into agency prose.
- **British English.**

---

## Evidence discipline

This is the thing that most often goes wrong. Hold the line on it.

- Separate conclusions by evidence strength. Say what is strong, what is directional, and what is a single voice.
- Name the boundary explicitly. Research based only on bookers cannot speak to non converting behaviour. Say so, on the page.
- Flag or remove unsupported claims. Do not hedge them into looking supported.
- Distinguish data accuracy from data bias. GA4 is accurate, but it is pointed at the final act of booking. That creates a targeting bias, not a measurement error. The Safari seven day cookie cap and cross device identity loss compound the gap.
- Booking data cannot validate the strategy that produced it.
- Confidence ratings on personas are load bearing. Meticulous Planner 90%, Pragmatic Day-Tripper 78%, Purposeful Adventurer 70%, Trusted Returner 65%. Build against the top two now. Treat the bottom two as hypothesis generating.

---

## Recurring judgement calls

Patterns that have come up repeatedly. Apply them by default and say when you are departing from them.

- **Multi-day and day tours are structurally different products.** Multi-day tours are trip anchors, booked before flights and accommodation. Day tours are itinerary fillers, booked after. Different marketing timing, different content, different conversion logic. Never write a recommendation that treats them as one funnel.
- **Qualification work belongs upstream.** Accommodation information and eligibility logic belong on the PDP, not in the booking flow. Late stage surprises cause abandonment.
- **Prefer cheap and reversible.** Rabbie's tends to over engineer responses to small feedback volumes. Recommend the cheap reversible fix until volume justifies a designed feature.
- **Component library abandonment is a governance problem**, not just a technical one. Custom builds proliferating outside the library indicate broken process.
- **Two genuine differentiators only:** driver-guides, and depth of service on logistics and accommodation. Small group size, no driving, and flexible commitment are category parity. Do not claim them as differentiators.

---

## Output conventions

- **Decks.** Rebuilt `.pptx` files via `pptxgenjs`. Not written slide content in chat. Convert to PDF with LibreOffice when a PDF is asked for. QA the text with `markitdown`.
- **Spreadsheets.** Excel with live formulas, not static values, wherever a chart or a model is involved.
- **Developer briefs.** ICE structure, in this order: Intent, Context, Expectations.
- **Prioritisation.** RICE. State the inputs, not just the score.
- **Liberandum palette.** PINK `#D02E5E`, NAVY `#123C64`. Open typographic layout. Whitespace and hairline dividers. Avoid card heavy designs.
- **File naming.** `YYYY-MM-DD_short-slug_vN.ext`.

---

## Tools in the stack

Analytics and testing: GA4, Algolia, VWO, Sleeknote.
Delivery and PM: monday.com (Rabbie's MarkComm backlog), Jira.
Build context: headless CMS, Supabase, Figma, component library (currently bypassed in practice).
Research: Grain for transcription, moderated depth interviews, exit survey recruitment.
Channels referenced: Viator, GetYourGuide, TripAdvisor. Microsoft Bookings for the private tours consultation pilot. Klarna, Apple Pay, Stripe for payment.

---

## Do not

- Do not put full participant names in any document intended to be shared.
- Do not present booker research as evidence about non bookers.
- Do not edit anything in `delivered/`.
- Do not invent a number. If a figure is not in `analysis/` or a source document, say it is missing.
- Do not produce a new persona set. Four exist. Use them.
- Do not write slide content in chat when a `.pptx` was asked for.

**Roles are a separate class and are not covered by the persona rule.** A persona describes who
someone is and how they decide. A role describes a job someone is holding on this particular trip,
which they can pick up and put down, and which any of the four personas can be holding. One exists:
R1 The Appointed Organiser, recorded in `personas.md` 17/09/2026 from the private tours research.
Layer it over a persona, never instead of one. Do not delete it as a fifth persona, and do not add a
second role without the same test: does it cut across the set, or does it cluster.
