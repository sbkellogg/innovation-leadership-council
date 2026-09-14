# Innovation Leadership Council (ILC)

Public site for the NC DPI Innovation Leadership Council — convening pages, reports, and
documents, published via GitHub Pages from the `main` branch root.

Live site: https://sbkellogg.github.io/innovation-leadership-council/

## Repository structure

- `index.html` — site landing page
- `convenings/<slug>/` — one folder per convening/event, each with its own `index.html` (or
  `.qmd` source) plus any local assets
- `reports/<slug>/` — analyses and reports
- `documents/` — static PDFs (charter, policies, etc.)
- `assets/` — shared images/CSS used across pages
- `.nojekyll` — disables GitHub's default Jekyll processing (needed so files/folders
  starting with `_`, such as Quarto output, are served as-is)

Pages are a mix of Quarto-rendered (`.qmd` sources rendered locally, then committed
alongside the output) and standalone HTML exports. Keep each page's supporting files
inside its own folder rather than at the repo root.
