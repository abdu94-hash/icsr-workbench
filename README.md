# ICSR Workbench

Free educational companion tool to *Mastering the ICSR: Case Processing in Modern Pharmacovigilance* by Dr. Hafez Selim, MD, PhD (Selim Medical Press, 2026).

**Live:** https://abdu94-hash.github.io/icsr-workbench/

Ten tools follow a case through the pharmacovigilance system. Each tab can be deep-linked from the book (for example `#dayzero`):

| # | Tool | Link | Book chapters |
|---|---|---|---|
| 1 | **Validity Checker**: four minimum criteria, pending-invalid follow-up plan, duplicate screen | `#validity` | Ch 3 |
| 2 | **Day Zero & Reporting Clocks**: Day 0, calendar-day deadlines by destination, internal targets, affiliate delay, significant follow-up, timeline | `#dayzero` | Ch 4 |
| 3 | **Reportability Triage**: six ICH E2A criteria per event, hospitalization exclusions, IME/DME flags, expectedness, causality, SUSAR test, postmarket classification by region | `#triage` | Ch 6, 8.2, 10 |
| 4 | **Severity ≠ Seriousness**: 2×2 matrix with the book's examples; CTCAE grade rules | `#severity` | Ch 7 |
| 5 | **Causality**: Naranjo calculator, WHO-UMC guided assessment, reporter vs sponsor, Appendix C crosswalk | `#causality` | Ch 8, Appendix C |
| 6 | **Narrative Builder**: eleven-part structure with case-type add-ons and a quality linter | `#narrative` | Ch 9 |
| 7 | **Case Lab**: six solved examples worked through the 16-step lifecycle | `#caselab` | Ch 1–10 |
| 8 | **Compliance & CAPA**: on-time rates, late-case Pareto and cluster detection, CAPA record | `#compliance` | Ch 11 |
| 9 | **Self-Assessment Quiz**: the book's 55 MCQs in study and exam modes | `#quiz` | All chapters |
| 10 | **Quick Reference**: searchable appendices and chapter summary tables | `#reference` | Appendices B–D |

Everything runs in the browser in a single self-contained `index.html` (no external scripts, fonts or trackers). Nothing you enter is sent anywhere; only terms acceptance, the last tab and quiz progress are kept in your browser's local storage. `mcqs.json` holds the question bank that is embedded in the page.

**Educational use only.** This is not a validated system and must not be used for regulatory submissions or real case decisions. You remain responsible for applying your company's SOPs and the current regulations. Do not enter patient-identifiable data. MedDRA terminology is not included; MedDRA is licensed by the MSSO on behalf of ICH.

© 2026 Hafez Selim, Selim Medical Press.
