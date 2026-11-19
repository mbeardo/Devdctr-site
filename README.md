# devdctr website

The landing page for [devdctr](https://github.com/mbeardo/portolan), a menu bar toolkit for developers on the Mac. One static HTML file and its images, with no build step, hosted on GitHub Pages.

- `index.html`: the whole page (styles and scripts inline)
- `images/`: real screenshots of the app, made with made-up demo projects
- `favicon.svg`, `favicon-*.png`, `apple-touch-icon.png`: icons

The screenshots come from the app's debug build. See "UI snapshots" in the app repository's README. Convert them with `cwebp -lossless -z 9 -exact in.png -o out.webp` and keep them at full size: the page shows them at exactly half their pixel width.

`.nojekyll` tells GitHub Pages to serve the files as they are.
