# Editing this website

This is a build-free static website. The portrait hero and interactive playground were retained from the published Site. The middle “A study in x” section was removed as requested; other visible text and styling were preserved.

## Files

- `index.html`: page title, description, headings, navigation labels, image description, and footer text.
- `style.css`: layout, typography, colors, and responsive styles.
- `app.js`: animated artwork, motion controls, artwork modes, and dynamic labels.
- `assets/bowen-portrait.jpg`: the original portrait.
- `.nojekyll`: tells GitHub Pages to serve the files directly.

## Your text and notes

Edit visible text in `index.html` directly. Dynamic labels such as “Pause motion”, “Resume motion”, and the artwork captions are in `app.js`.

When adding notes or sections, keep existing `id` values, canvas elements, and button `data-mode` attributes unless you also update the JavaScript that uses them. Place additional images or files in `assets/` and use relative links.

No package install or build is required. With GitHub Pages set to the `main` branch and `/ (root)`, committed changes publish automatically after the Pages build finishes.


## Personal Agent pages

- `privacy.html` and `terms.html` contain the supplied Chinese privacy policy and terms.
- The homepage footer identifies this site as the Personal Agent homepage and links to both policy pages.
- The contact email is repeated in each page footer and in the privacy policy contact line. Update all occurrences together.
- Policy and footer styles are appended to `style.css`; the existing artwork and `app.js` are unchanged.
