# Sarvesh Dharmadhikari · DevOps Engineer portfolio

Static single-page portfolio (no build step), deployed to GitHub Pages by `.github/workflows/pages.yml`.

- Deploys on every push to `main`.
- Every day at **06:00 IST** it redeploys with the next dark theme from `themes/`
  (midnight → noir → phosphor → aurora → blueprint → kube).
- To force a theme: Actions → *Deploy to GitHub Pages* → *Run workflow* → enter a theme name.

Content edits must be made in every file in `themes/` (they share the same content; only the styling differs).
