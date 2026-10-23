# Variation Compass

A single-page decision tool for classifying EU post-authorisation variations under
**Commission Guidelines C/2025/5045** (OJ C, 22.9.2025), applicable from 15 January 2026.

Every code and outcome in the classification annex is encoded as a structured rule, so each
result traces back to a code, its conditions and its documentation list.

## What it does

- **Classify** — navigate the annex by area and change, and land on a typed outcome (IA, IA<sub>IN</sub>, IB, II, Extension)
- **Submission & memo** — collect changes into a basket and export a classification memo as Markdown or PDF
- **Timeline planner** — map procedural clocks onto calendar dates
- **Practice** — self-test on classification decisions
- **What changed in 2026** — the delta from the previous guideline, including the new code structure
- **Reference** — variation types, extensions, grouping and worksharing, glossary

## Running it

One self-contained file. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

No build step, no dependencies to install. jsPDF is loaded from a CDN for PDF export; everything
else runs offline.

## Scope and limits

Human medicinal products under Directive 2001/83/EC and Regulation (EC) No 726/2004. The texts
are condensed paraphrases of the official wording. Classification remains the marketing
authorisation holder's responsibility — check the official guideline, any Article 5
recommendations published by EMA/CMDh, and the procedural guidance before filing.

Decision support only. Not regulatory or legal advice.

## Author

**Dr Hatem Raad, MD** — physician (emergency medicine), pharmaceutical medical affairs,
Master of Drug Regulatory Affairs candidate at the University of Bonn.

- s.raaed@hotmail.com
- [Labsense.org](https://labsense.org) · [MyPrivateDoctor.org](https://myprivatedoctor.org)
