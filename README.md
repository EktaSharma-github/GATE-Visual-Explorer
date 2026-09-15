# GATE 2027 — Two-Paper Combination Visual Explorer

An interactive browser-based visualization of the GATE 2027 two-paper combination table.

## What it shows

- Interactive directed network of all 30 GATE papers
- 118 primary → secondary relationships
- Search and paper-focus controls
- Top-paper option ranking
- Domain clusters
- 30 × 30 primary → secondary matrix
- Paper-level combination details
- No external JavaScript library required

## Run locally

Open `index.html` in a modern browser. The graph is generated entirely with browser JavaScript and SVG.

## GitHub Pages

This repository includes a GitHub Pages deployment workflow at `.github/workflows/pages.yml`.

If Pages has not been enabled yet, go to **Settings → Pages** and set **Source** to **GitHub Actions**. After the workflow completes, the live visualization will be:

`https://ektasharma-github.github.io/GATE-Visual-Explorer/`

## Data note

The visualization uses the GATE 2027 two-paper combination table supplied for this project. The clusters are analytical groupings and are not official GATE classifications. Always verify the final official combination list on the GATE 2027 website before making registration decisions.