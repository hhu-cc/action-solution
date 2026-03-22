# action_solution

Static proposal publishing repo for insurance/customer proposal HTML.

## GitHub Pages

Recommended Pages settings:
- Source: Deploy from a branch
- Branch: main
- Folder: /(root)

## Structure

- `index.html` — root landing page for GitHub Pages
- `proposals/current/<proposal-id>/` — current live proposal pages
- `proposals/archive/<proposal-id>/` — archived proposal versions
- `proposals/index.json` — machine-readable proposal index
- `.nojekyll` — disables Jekyll processing for static paths
