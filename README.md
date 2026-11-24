# Ajinkya Kamat — Portfolio

A static, responsive personal engineering portfolio. No framework, external fonts, analytics, or build dependencies.

## Local preview

Open `index.html` in a browser, or serve the repository root with:

```sh
python3 -m http.server 8000
```

## Publishing

The repo is intended for `https://ajinkyakamat.github.io/`. Review the `feat/portfolio-v1` branch and merge to `main` when approved. Configure GitHub Pages to deploy from `main` at the repository root, if this is not already enabled.

## Content boundaries

- Current FieldAI responsibilities are summarized at a high level; avoid disclosing internal hardware designs or proprietary details.
- Previous work includes Systemantics, AVL, Carnegie Mellon, and the University of Washington.
- IvLabs membership, paper, and patent counts are explicitly **organization-wide** figures.
- APSL and other stealth work are intentionally excluded.
- The master career archive and resume source are maintained in a **separate private repository**; this site does not link to them.
- External paper links point to public sources; no paper PDFs are redistributed.

## Next iterations

Develop project case studies for RoMan, ReBiS, Swayat, and CMU grasping after permission/disclosure review. Maintain the published resume PDF using the approved private LaTeX source.

## Files

- `index.html` — page structure and content
- `styles.css` — responsive editorial design
- `resume.pdf` — approved two-page PDF for public download, built from the private LaTeX resume
- `.nojekyll` — static GitHub Pages passthrough

## Archival GIF demonstrations

RoMan, Good Cherrybot, ReBiS and Swayat GIFs are temporarily loaded from the author's older public portfolio at `kamatajinkya2.github.io/images/` and have their original project captions. Their source filenames were checked against the old portfolio's `_config.yml` and asset paths in its GitHub repository. This avoids duplicating potentially large animation files in the new repo while the layout is reviewed. For long-term durability, migrate/optimize the assets to this repository or a controlled media host in a separate change; do not rely indefinitely on cross-site media. GIF playback is automatic, so prefer accessible still/poster alternatives or MP4/WebM for a final media-heavy version.

## Public resume and LinkedIn

- LinkedIn: `https://www.linkedin.com/in/ajinkya-kamat/` from the author's original public portfolio.
- `resume.pdf` is the approved two-page LuaLaTeX PDF compiled from `resume.tex` at the private `ajinkyakamat/resume` repository `main` branch (release version at initial publication). Its CI build confirmed two pages with a PDF parser.
- Visitors can download the PDF directly from the portfolio. The public site deliberately does **not** maintain an independent HTML resume or public LaTeX source file.
- When the private resume changes, regenerate `resume.pdf` from the approved release and replace the public PDF through a feature branch and PR. Do not publish the private master career archive.
