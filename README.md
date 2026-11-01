# Sarvesh Dharmadhikari · DevOps Engineer portfolio

Static single-page portfolio (no build step), deployed to GitHub Pages by `.github/workflows/pages.yml`.

- Deploys on every push to `main`.
- Every day at **06:00 IST** it redeploys with the next design, in the order listed in `themes/rotation.txt`
  (31 designs: 6 classic themes, 7 light DevOps, 6 DevSecOps, 6 gaming, 5 game-UI and 1 crafting).
- Every design is also live at `/<name>.html`, and `/designs.html` lists them all.
- To force a design: Actions → *Deploy to GitHub Pages* → *Run workflow* → enter a name from `rotation.txt`.
- To drop a design from the rotation, delete its line from `rotation.txt`.

Content edits must be made in every file in `themes/` (they share the same resume content; only the presentation differs).
