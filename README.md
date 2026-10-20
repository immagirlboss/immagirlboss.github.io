# Akbota Kengeskhan — Portfolio

Static software engineering and applied AI portfolio for GitHub Pages.
No build step, dependencies, third-party scripts, or external fonts.

## Sections

1. Introduction with an original SVG system map.
2. Selected projects, directly after the introduction, grouped by theme.
3. Digital Twin case study: retrieval architecture, decisions, and limitations.
4. Expertise tied to concrete project examples.
5. Technical approach illustrated by engineering decisions.
6. Experience and education, followed by About and contact.

All eight project entries, including Crepiks, expand to show a local picture,
caption, full-size image link, and relevant technical context. Expanded project
cards use the full content width. Screenshots retain their original colors.

The visual direction combines restrained editorial layouts with a futuristic
white and cool grey palette, fine technical grids, and original system diagrams.

## Update

Edit content in `index.html` and visual styles in `styles.css`.
Keep project entries in their corresponding `data-group` sections. Theme filters
progressively enhance the page; all projects and native disclosures work without
JavaScript. In-page links reveal a project if its theme was filtered out.
Preserve prototype labels, contribution boundaries, and evaluation limitations.
Do not invent dates, metrics, credentials, or employment history.

## Preview and publish

Run `python3 -m http.server 8000` from the repository root.
Publish the main branch from the repository root with GitHub Pages.
The profile repository is `immagirlboss.github.io`.

## Project image sources

- `assets/mangalens.png`: existing portfolio screenshot.
- `assets/vrify-preview.jpg`: `immagirlboss/vrify`, `vrify-preview.jpg`.
- `assets/rewear-schema.png`: `Sofiia-Bilyk/ReWear`, `docs/schema.png`.
- `assets/crepiks-practice.png`: `Azatyk/crepiks-academy-frontend`,
  `src/assets/images/explanation-macbook-mockup-practice.png`.
- `assets/*-system.svg`: original architecture illustrations based on project
  READMEs; labeled as illustrations rather than application screenshots.

Replace illustrations with authentic screenshots when available. Keep descriptive
alt text, intrinsic image dimensions, and full-size links when changing images.

## Preserved from the published portfolio

The supplied project screenshots (`digital-twin.jpg`, `rewear.jpg`,
`ryoiki-tenkai.jpg`, `soul-society.jpg`, `crepiks.jpg`) and updated
`mangalens.png` are preserved from the existing main branch and used in expanded
entries. The original `portrait.jpg` is retained as an available asset.
The published Digital Twin V3 validation findings and Crepiks grant milestone
are retained in the redesigned project content.
