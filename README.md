# Umair Hassan: personal site

Plain static site: no framework, no build step. GitHub Pages serves the folder as-is.

```
index.html      all content (edit text here)
css/style.css   fonts + responsive rules
fonts/          self-hosted Source Serif 4 and IBM Plex Mono (latin subsets)
assets/         CV PDF
favicon.svg
```

## Preview locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## Deploy to GitHub Pages

1. Create a repo named `umair-hassan2.github.io` (gives you `https://umair-hassan2.github.io`) and push the contents of this folder to `main`.
2. Repo Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.

For a project repo (any other name) the site lives at `https://umair-hassan2.github.io/<repo>/`. All paths are relative, so it works either way.

## Updating content

- Colours: all colours are tokens at the top of `css/style.css` (`--accent`, `--bg`, …), with a light set and a dark set. Change the accent there; `index.html` only uses `var(--…)`.
- Dark mode follows the visitor's system setting; the half-circle button in the nav overrides it (remembered per browser).
- Link preview: `assets/og.png` (1200×630). The `og:image` URL in `index.html` assumes the site lives at `https://umair-hassan2.github.io/`.
- New CV: replace `assets/Umair_Hassan_CV.pdf` (keep the filename).
- Writing section: the "First posts soon" paragraph is in the `#about` block; replace it with a list of links when you have posts.
- Headings use Instrument Serif (`fonts/instrument-serif-400.woff2`); body text stays Source Serif 4.
- Paper grain: `assets/grain.png`, laid over the page at 5% opacity (`body::after` in `css/style.css`).
- Printing (Ctrl+P) shows a one-page summary instead of the web layout. Its text lives in the `print-only` block at the bottom of `index.html`, so update it when you update the page.
