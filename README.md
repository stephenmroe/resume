# Stephen Roe — Interactive Resume

**[→ View the live resume](https://stephenmroe.github.io/resume/)**

An interactive, single-page reimagining of my resume — built as a self-contained
`index.html` with vanilla JavaScript (no framework, no build step). All content lives
in a JSON island near the top of the file; the rest is a small renderer that wires up
scroll progress, reveal-on-scroll, count-up stats, SVG animation, nav spy, and a
filterable "data stories" section.

## At a glance

**Stephen Roe** — Principal Full-Stack Engineer for complex data products.

I turn complex, high-volume datasets — financial, royalty, clinical, operational — into
polished software that helps sophisticated users explore, understand, and act. The work
sits at the intersection of full-stack engineering and quantitative data: analytical
products where the interface *is* the decision workflow, not just another chart on a screen.

### Selected data stories

- **ERP data → exploratory AI analysis** — *Cauzzy.ai, 2025–now.* Client-facing AI
  financial-analysis product over NetSuite data; owned the architecture end to end
  (web UI, APIs, retrieval/RAG, auth, AI reasoning, production delivery). Beta in 4 months.
- **Royalty statements → analyzable assets** — *Iconic Artists Group, 2022–2024.* Built a
  royalty-management platform from scratch, ingesting statements from 60+ payors into a
  single portfolio view — 150M+ rows made analyzable.
- **Physiological data → clinician insight** — *Modulim, 2019–2022.* Led the
  re-architecture of an enterprise medical-device SaaS platform for clinicians
  interpreting complex physiological data.

### By the numbers

- **150M+** rows made analyzable, far beyond the reach of a spreadsheet
- **20K+** statements automated from semi-structured documents
- **$2.25M** estimated annual labor savings from automation
- **4 months** from zero to a live, client-facing AI finance product

### Toolkit

React · Next.js · TypeScript · JavaScript · D3-oriented viz · SVG / Canvas · Responsive UI ·
Accessibility · APIs · SQL · Python · C# / .NET · Azure · AWS · AI / RAG

### Experience

- **2013 — now** · Principal Software Engineer · Lateral Data Solutions
- **2025 — 2026** · Founding Senior Software Engineer · Cauzzy.ai
- **2022 — 2024** · Principal Software Engineer · Iconic Artists Group
- **2019 — 2022** · Director of Software Engineering · Modulim
- **2005 — 2015** · BI, data warehouse & enterprise software roles

## Contact

- **LinkedIn:** [in/stephen-roe-architect](https://www.linkedin.com/in/stephen-roe-architect/)

## Editing

To update content, edit the JSON inside the `<script type="application/json" id="resume-data">`
block in [index.html](index.html). The renderer below it needs no changes for content edits.
