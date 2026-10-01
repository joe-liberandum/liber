# Navigation and IA

The wayfinding layer. Two linked workstreams, one in QA and one in build.

**Figma.** Website Navigation Redesign, May 2026.
**Scoping doc.** Google Doc, navigation redesign.
**Owner.** Tech. Supporting: Content, Ecommerce, Salience.

---

## Navigation redesign

**In QA.** Apr to Aug 2026. All four personas, Desire phase. 20.5 days combined with IA restructure. RICE rank 6.

### The structure

Primary navigation organised around how customers arrive, not how Rabbie's organises its business:

- Departure City
- Destinations
- Duration
- Interests
- Most Popular
- New for 2026
- Sale

### Evidence

74% of homepage visitors use neither the navigation nor search. Search converts at 23.98%, navigation at 18.73%. The stronger path is the one fewer people take, and most people take neither.

### Scope

Navigation component redesign, mobile accordion, hover states. New landing pages must be coordinated with this work. Two open business questions get resolved inside it: where the late availability link sits, and where sale placement goes.

### Dependencies

Salience alignment. URL taxonomy standardisation. Landing page readiness.

### Testing

Test after launch, on nav label set and category order. The nav shipped, so this test is due now. See `test-variants/`.

---

## Information architecture restructure

**In Build.** Apr to Aug 2026. 10 days standalone. RICE score 0.900, higher than the nav it sits under.

Site structure and URLs are not organised around customer intent or SEO-relevant categories, weakening wayfinding and organic visibility together.

### Scope

Full site map review. URL structure. Page templates for each page type: homepage, PLP, PDP, landing page, late availability.

**This is the largest single design workstream on the list.** Phase it: agree structure first, then design templates in order of traffic priority. Do not attempt templates before structure is agreed.

### Not suitable for CRO test

Structural change. Validate via SEO and search metrics rather than an A/B test.

### Dependency for the design system

The UX design system depends on IA page structure being agreed. Templates for five page types are in scope across this and the landing page work with no shared component definition. Every week that gap stays open, components get rebuilt per initiative and drift between templates.

---

## Homepage entry point

Specified in the persona work, not currently a tracker initiative.

**Problem.** Browse intent and book intent are forced through the same front door. The homepage search widget demands a destination and a date before a flexible planner has decided anything. Segment D named this directly as a need to split the inspirational research side from the actual booking side.

**Recommendation from research.** Make browse-without-dates the default homepage entry point.

**Status.** Not scoped. Should be resolved inside the nav and IA work rather than as a separate item, since both touch the same surface.

---

## Coordination constraint

Salience owns SEO. The nav redesign and IA restructure both change URL structure and category taxonomy. Coordinate before shipping anything that touches either, and do not run CRO tests on the nav that would clash with SEO changes landing at the same time.
