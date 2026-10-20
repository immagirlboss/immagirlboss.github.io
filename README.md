# Akbota Kengeskhan — Portfolio

Static software engineering and applied AI portfolio for GitHub Pages.
No build step, dependencies, third-party scripts, or external fonts.

## Sections

- Introduction: software engineering and applied AI.
- Selected projects, grouped by theme.
- Digital Twin evaluation note with preliminary validation results.
- Technical skills.
- Experience and education.
- Contact links to GitHub and LinkedIn.

The page uses white and light grey, consistent name typography, generous spacing,
and minimal borders. Abstract hero diagrams and the former Approach and About
sections have been removed.

## Project windows

View project opens a native modal dialog containing the project's screenshot,
technical notes, and repository link. Close it with the Close button, Escape, or
by clicking outside the window. Focus returns to the original project control,
and the underlying list keeps its scroll position. Native dialog behavior traps
focus and makes the background inactive while open. Without JavaScript or native
dialog support, the same content remains accessible through inline disclosures.

All eight entries have a local image and a full-size link. Real project
screenshots are preserved; BA Eats uses a labeled system illustration.

## Update

Edit content in `index.html` and styles in `styles.css`.
Keep each project in its corresponding `data-group` section. Theme filters
progressively enhance the page. Preserve prototype labels, contribution
boundaries, and evaluation limitations.

## Preview and publish

Run `python3 -m http.server 8000` from the repository root.
GitHub Pages publishes the main branch from the repository root.
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
