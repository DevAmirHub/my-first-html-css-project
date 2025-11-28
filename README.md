# My First Front-End Project

Static mockups for two Persian marketing concepts built only with HTML and CSS.
They are ready to be published to GitHub as-is or used as a starting point for a
more dynamic stack.

## Project structure

- `wireframe7/` – Landing section with the “اصلش اینه” hero title, four feature
  cards (time, affordability, credibility, cash purchase) and a prominent CTA
  button animated via staggered slide-in effects.
- `wireframe11/` – Quiz-style layout that keeps the same hero title, shows a
  featured image, renders a multi-option question with radio buttons, and
  highlights the “Next Question” action.
- Each folder bundles its own `index*.html`, stylesheet, the `Vazir.woff` font,
  and reference PNG assets (both UI exports and the original wireframes).

## Technology

- HTML5 semantic markup with `lang="fa"`/`lang="en"` declarations for
  localization hints.
- Vanilla CSS3 for layout, responsive breakpoints, animations, and the custom
  Vazir typeface.
- No build tooling or package manager dependencies.

### Getting started locally

1. Clone the repository or download the ZIP.
2. Open `wireframe7/index.html` or `wireframe11/index2.html` directly in a
   modern browser, or serve a folder with a lightweight static server such as:
   ```
   cd wireframe7
   python -m http.server 8000
   ```
3. Preview the mockups and tweak the HTML/CSS as needed.

## Publishing to GitHub Pages

Because each wireframe is self-contained, you can publish them separately:

- Create a branch (for example `wireframe7`) that keeps only the corresponding
  folder contents at the root, then enable GitHub Pages → Deploy from branch.
- Repeat for `wireframe11`, or host the second mockup from a different branch.
- Alternatively, keep the current structure and rely on GitHub Pages’ `docs/`
  folder: copy one wireframe into `docs/` so it becomes the default public page.

Remember to keep the PNG assets and `Vazir.woff` font in the same directory as
their HTML/CSS counterparts so that image references and the custom typeface
load correctly.

## Future enhancements (optional)

- Internationalize the copy by providing English text alternatives to the
  placeholder Persian content.
- Add a shared landing page (`index.html` in the repo root) that links to each
  wireframe for easier navigation on GitHub Pages.
- Convert repeated styles into CSS variables or a utility partial if you plan to
  expand the project.


