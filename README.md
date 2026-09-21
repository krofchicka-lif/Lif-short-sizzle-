# Love It Forward — presentation

Static site. No build step, no dependencies. `index.html` is fully self-contained: fonts, images, textures, CSS and JavaScript are all embedded, so it works from any path (Netlify root or a GitHub Pages project URL).

## Contents

- `index.html` — the 13-slide presentation
- `.nojekyll` — tells GitHub Pages to serve files as-is
- `README.md` — this file

## GitHub Pages

1. Upload the extracted contents of this folder to the repository root (`index.html` must be at the root, not in a subfolder).
2. Settings → Pages → Deploy from a branch → `main` and `/ (root)`.
3. Save. The site publishes at `https://<user>.github.io/<repo>/`.

## Netlify

**Drag and drop:** app.netlify.com → Sites → drag this extracted folder (the one containing `index.html`) onto the drop zone.

**From GitHub:** Add new site → Import an existing project → pick the repository. Leave the build command empty and set the publish directory to the repository root (`.`).

## Navigation

Click or tap anywhere on the opening slide to advance. Use the Prev / Next controls at the bottom, or the left and right arrow keys. The final slide keeps Prev and the live demo link.
