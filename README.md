# Akbota Kengeskhan — Portfolio

Static portfolio on GitHub Pages. No build step or dependencies.

## Add or replace pictures without editing code

1. Open this repository on GitHub and enter the `assets` folder.
2. Choose **Add file → Upload files**.
3. Upload your picture using the exact filename from the table below. To replace an existing picture, upload the new file with the same name.
4. Commit the change to `main`. GitHub Pages publishes it automatically. Refresh the site when publication finishes.

| Picture | Exact filename inside `assets/` |
| --- | --- |
| Your portrait | `portrait.jpg` |
| Digital Twin | `digital-twin.jpg` |
| ReWear | `rewear.jpg` |
| MangaLens | `mangalens.png` |
| Ryoiki Tenkai | `ryoiki-tenkai.jpg` |
| BA Eats | `ba-eats.jpg` |
| Soul Society | `soul-society.jpg` |
| Crepiks Academy | `crepiks.jpg` |

Use a real JPEG for `.jpg` filenames and a real PNG for `.png`; export to the right format rather than only changing the extension. Screenshots around 1600 px wide are sufficient; a vertical portrait works best. Keep files reasonably small (ideally under 1 MB).

Project images show the whole picture without cropping. The portrait fills its frame and may crop the edges. Until you upload an image, the project keeps its typographic cover. MangaLens already has a screenshot. This works for all visitors; it does not depend on a local browser upload.

## Edit project details

Each plaque is a native `<details class="project">` in `index.html`. Click anywhere on its collapsed plaque, or focus it and press Enter or Space, to expand the description, role, tools, and repository link. More than one plaque can stay open.

Edit the text inside that project's `.project-details` block to update the description or role. Edit its `.stack-list` items to change the tools. The short summary lives inside `.project-body`.

## Publishing and motion

GitHub Pages publishes the `main` branch from the repository root. The decorative spider lily rotates once every 60 seconds. The footer button pauses it; reduced-motion preferences disable animation.
