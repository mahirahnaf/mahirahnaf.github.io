# Portfolio — Mahir Ahnaf

Personal portfolio site: competitive programming profiles, contest results, and education.

**Live:** https://mahirahnaf.github.io/Portfoilio/

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The whole page — nav, hero, about, education timeline, CP section, footer |
| `style.css` | All styling |
| `image_79c1e8.png`, `image_79c207.png` | Hero and about photos |

Static HTML/CSS — no build step. Open `index.html` in a browser to preview locally.

## Deployment

`.github/workflows/deploy-pages.yml` publishes the repository root to GitHub Pages on
every push to `main`, and can also be run manually from the Actions tab. Pages is
configured with **Source: GitHub Actions**.
