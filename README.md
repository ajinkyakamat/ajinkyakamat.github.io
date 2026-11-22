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

Add original project images or demos after permission/disclosure review, and develop project case studies for RoMan, ReBiS, Swayat, and CMU grasping. A public resume PDF can be added as a separate deliberate release.

## Files

- `index.html` — page structure and content
- `styles.css` — responsive editorial design
- `.nojekyll` — static GitHub Pages passthrough

## Archival GIF demonstrations

RoMan, Good Cherrybot, ReBiS and Swayat GIFs are temporarily loaded from the author's older public portfolio at `kamatajinkya2.github.io/images/` and have their original project captions. Their source filenames were checked against the old portfolio's `_config.yml` and asset paths in its GitHub repository. This avoids duplicating potentially large animation files in the new repo while the layout is reviewed. For long-term durability, migrate/optimize the assets to this repository or a controlled media host in a separate change; do not rely indefinitely on cross-site media. GIF playback is automatic, so prefer accessible still/poster alternatives or MP4/WebM for a final media-heavy version.

## Public resume and LinkedIn

- LinkedIn: `https://www.linkedin.com/in/ajinkya-kamat/` (matching the original portfolio and externally verified FieldAI profile).
- `resume.html` reproduces the **released** `resume.tex` from the separate private resume repository as a public, print-friendly HTML document. The source repository itself stays private.
- Visitors can open the resume and use **Print / Save as PDF** to create an A4 PDF on their devices. This is **not** a pre-generated or directly downloadable PDF file. If a fixed PDF download is desired, publish an approved PDF as `resume.pdf` in this public repository and update the CTA after checking the file.
- Updates to `resume.tex` in the private repository must be synchronized manually to `resume.html` until an intentional publication pipeline is established.
