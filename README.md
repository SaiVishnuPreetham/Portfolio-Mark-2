# Portfolio Mark 2 — Sai Preetham

Personal portfolio website for **Sai Vishnu Preetham**.

## Live site

This repository is deployed with **GitHub Pages** (branch: `gh-pages`).

- Open the site: `https://saivishnupreetham.github.io/Portfolio-Mark-2/`

## Tech stack

- Static site (GitHub Pages)
- Front-end build output (bundled assets under `assets/`)
- HTML entrypoint: `index.html`

## Repository structure

- `index.html` — App entrypoint (mounts `#root` and loads the bundled JS/CSS)
- `assets/` — Built JS/CSS bundles
- `images/` — Images used by the site
- `favicon.svg` — Site icon
- `.nojekyll` — Disables Jekyll processing for GitHub Pages

## Local preview

Because this branch contains **built static files**, you can preview it locally with any static server.

### Option A: VS Code Live Server

1. Install the **Live Server** extension.
2. Right-click `index.html` → **Open with Live Server**.

### Option B: Python

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Customization

If you want to change content/styling:

- Edit the **source project** (wherever you develop your portfolio), rebuild, then deploy the generated files to this `gh-pages` branch.

## License

If you’d like this to be open-source, add a license (MIT is common for portfolio sites). Otherwise, you can remove this section.
