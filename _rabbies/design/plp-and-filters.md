# PLP and filters

The tour listing page. Currently blocked on foundational data work.

---

## Improve PLP data structure

**Blocked** on July CRO test completion. Owner Tech. **Effort TBC. Confidence 0.6.**
**Scoping doc.** Google Doc, PLP data structure.

The frontend does not have access to the tour data needed to power reliable filtering or to show relevant information on tour cards. This is the foundational blocker for every other PLP improvement.

### Evidence

Customers say filters do not work. Some returning visitors gave up looking for tours they had booked before, which is a serious signal: those are the highest-intent people on the site.

Tour stop data may not be present in the underlying structure. That affects three separate things: filter reliability, SEO discoverability for place-name searches, and any future compare-tours feature.

### The cheapest thing outstanding

**Filter usage data from the PLP has never been pulled.** Which filters fail, and how often. It is the cheapest item on the entire backlog and everything else about filters depends on it. Currently the position rests on qualitative reports with no instrumentation behind it.

Do not design filter changes before this exists.

---

## Tour stops in the data structure

**Tag: DATA.** Awareness and Interest phases.

People search Google for specific places they want to visit. If tour stops are not in the site data, Rabbie's does not appear for those searches.

Needed for:
- Place-name organic search visibility
- Compare tours
- New paid search landing pages
- Showing stops on PLP and PDP cards

Status: check not completed. Blocks item 03 in the original initiatives list and the compare feature in Personalisation.

---

## Show tour stops and end dates on PLP and PDP

**Tag: DESIGN.** Interest and Desire.

One customer emailed Rabbie's to check whether two tours fitted together because end dates were not shown. Another wrote her own checklist to compare stops.

End dates on the calendar is now a Buy Box sub-task at 1.5 days, RICE rank 3. See `buy-box-spec.md`. Stops on cards remains blocked on the data structure check.

More urgent than it was, because paid search is not converting well and these cards are where that traffic lands.

---

## Personalisation on PLP and PDP

**To do.** Owner Ecommerce. 5.5 days. RICE rank 12. Algolia-based.

Related tours, recently viewed, and "you may be interested in" modules on landing pages and PDPs.

**Evidence.** Customers compare manually using spreadsheets and multiple tabs, and struggle to re-find tours of interest. One participant compared tour maps by hand. Another texted links to her mum because there was no other way to share.

**Sequencing.** Compare needs the tour stop data check first. Related tours and recently viewed can ship independently of it.

**Rationale from trading.** With demand down, each visit has to work harder.

---

## Not yet scoped

- Filter reliability fix itself, as distinct from the data structure underneath it
- Late-minute availability surface for tours departing in the next 7 to 14 days, recommended in the persona work and partly absorbed by the late availability landing page work
- Sort order options. Late availability needs soonest-first; nothing establishes what the default PLP sort should be
