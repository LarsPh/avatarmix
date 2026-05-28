# AvatarMix Project Page

This repository hosts the project page for:

**AvatarMix: Identity-Preserving Cross-Avatar Composition for Outfit Personalization**  
Zhaorong Wang, Yoshihiro Kanamori, Yuki Endo  
University of Tsukuba  
CVPR 2026 Findings

Project page URL:

```text
https://larsph.github.io/avatarmix/
```

## Current status

This is an initial under-construction project page prepared for the CVPR poster QR code. The first version intentionally does not include images, videos, paper PDF, poster PDF, or code release links.

Current public sections:

- Paper title, authors, affiliation, and contact
- Short landing description
- Abstract / overview
- Task and motivation
- Method overview
- Training strategy for artifact refiners
- Quantitative results summary
- Key takeaways
- Limitations and future work
- Preliminary citation placeholder

## How to deploy on GitHub Pages

This repository is intended to be a GitHub Pages project site under the `larsph.github.io` personal site.

Recommended repository name:

```text
avatarmix
```

Expected URL after GitHub Pages is enabled:

```text
https://larsph.github.io/avatarmix/
```

In GitHub:

1. Go to `Settings` → `Pages`.
2. Set `Build and deployment` to `Deploy from a branch`.
3. Choose branch `main` and folder `/ (root)`.
4. Save and wait for the Pages deployment to finish.

## How to update this page later

The current `index.html` contains several `coming soon` placeholders. Replace them when release materials are ready.

Suggested future paths:

```text
static/pdfs/wang_avatarmix_cvprf26.pdf
static/pdfs/wang_avatarmix_cvprf26_poster.pdf
static/images/teaser.jpg
static/images/method_overview.jpg
static/videos/avatarmix_teaser.mp4
```

Suggested links to update in `index.html`:

- Paper button
- Poster button
- Video button
- Code button
- OpenGraph preview image
- BibTeX citation
- Qualitative results / media sections

## Local preview

From the repository root, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Template note

The `index.html` is written to work with the common Academic Project Page template structure. Keep the template's existing `static/` folder so that Bulma, Font Awesome, Academicons, and template-specific CSS/JS continue to load correctly.

## Contact

Zhaorong Wang  
University of Tsukuba  
Email: zhaorong.wang1997@gmail.com  
Website: https://larsph.github.io/

