# Training Week

A mobile-friendly, no-login reference site for the current training week, published via GitHub Pages.

**Pages:**
- `index.html` — this week's plan-file prescription, day by day (not a log, not a comparison against actuals). Regenerated at the start of each week.
- `sc.html` — the S&C A/B checklist, tap-to-check. Linked from `index.html`'s Thursday/Sunday rows via `sc.html#a` / `sc.html#b`, which auto-select the matching tab.

**Source of truth:** `athlete-profile.md` and the current Training Plan file in the private [`calmath/running`](https://github.com/calmath/running) repo. This repo is a public, generated mirror — kept in sync by hand whenever the plan or the S&C template changes there.

Nothing sensitive lives here by design — day-by-day session detail and the S&C routine only, no training log data, no personal identifiers beyond the routine itself.

Live site: https://calmath.github.io/sc-checklist/ (Settings → Pages → Deploy from a branch → `main` / `/root`).
