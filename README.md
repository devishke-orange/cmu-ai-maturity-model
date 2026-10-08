# CMU AI Adoption Maturity Model: interactive map

An unofficial, interactive study aid for **The AI Adoption Maturity Model v1.0** by the Software Engineering Institute (SEI) at Carnegie Mellon University and Accenture.

**Live site:** https://devishke-orange.github.io/cmu-ai-maturity-model/

## What's here

| Page | What it shows |
|---|---|
| [`index.html`](index.html) | An interactive graph of the model. Switch layers on and off (dimension groups, dimensions, maturity levels, goals, practices, example artifacts, cross-dimension links), organize by dimension or by maturity level, view it as a tree or a radial mind map, and filter to the areas a target level needs. |
| [`levels.html`](levels.html) | The model by maturity level. Pick one of the five levels for the organizational unit to see the capability areas Table 2 requires at that level and below, grouped by dimension, with the maturity indicators for that level highlighted. Each capability area opens onto its goals, and each goal onto its practices. |
| [`reference.html`](reference.html) | The full list: every dimension, capability area, goal and practice, with the maturity level each capability area completes, the maturity indicators, and page references to the book. |

The model at a glance: 8 dimensions, 25 capability areas, 64 goals and 244 practices. Each capability area sits at the maturity level its goals complete (Table 2, p. 85). A capability area's rating is capped by its weakest maturity indicator (Accountability, Planning, Resourcing), and a dimension's rating is capped by its weakest capability area (p. 87).

All three pages are single static HTML files, linked by a tab bar at the top. The graph loads D3 from cdnjs, all pages load fonts from Google Fonts, and none needs a build step. To view them locally, open `index.html` in a browser.

## Copyright and attribution

The AI Adoption Maturity Model, including its structure, dimensions, capability areas, goals, practices, maturity levels and maturity indicators, is **© 2026 Carnegie Mellon University**. It was developed by the Software Engineering Institute at Carnegie Mellon University together with Accenture.

- This project is **not affiliated with, sponsored by or endorsed by** Carnegie Mellon University, the Software Engineering Institute or Accenture.
- Goal and practice text on these pages is **condensed and paraphrased** for study purposes. It is not the official wording. Consult the original publication for the authoritative text before relying on or quoting it.
- No license is granted here for the model content. All rights in the original work remain with Carnegie Mellon University.
- Carnegie Mellon® and CERT® are registered in the U.S. Patent and Trademark Office by Carnegie Mellon University.

If you are a rights holder and would like this content changed or removed, please open an issue.
