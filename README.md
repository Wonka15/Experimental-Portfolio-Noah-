# Noah — Macintosh Studio Portfolio

An experimental, single-page portfolio built around a 3D Macintosh SE scene, with a complete text-first portfolio underneath it.

## What is included

- Interactive Three.js Macintosh SE scene with orbit controls and a floppy-disk boot interaction.
- Plain HTML Work, About and Contact sections that remain available if WebGL or the 3D module fails.
- A visible **Skip to work** link so visitors can reach projects without the intro.
- Project case studies with problem, process and result summaries.
- Responsive layouts, keyboard-accessible dialog close behavior (Escape), visible focus styles and reduced-motion support.
- Page description, Open Graph/Twitter preview metadata and SVG favicon.

## Run locally

Open `index.html` in a modern browser. The 3D scene imports Three.js and OrbitControls from jsDelivr, so an internet connection is required for the 3D experience. The text portfolio itself is plain HTML and CSS and remains available if the CDN or WebGL is unavailable.

## Publish with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/(root)` folder, then save.
4. GitHub Pages publishes at:

   https://wonka15.github.io/Experimental-Portfolio-Noah-/

## Before sharing publicly

- Add a public Luma Glass project repository or live demo URL when it is ready. The current card links to the GitHub repositories list because a dedicated project URL was not present in the source material.
- Add a public résumé PDF as `resume.pdf` if you want one hosted here. Until then, the contact section offers an email link to request a copy.
- Replace the social preview artwork if you have a final render of the Macintosh scene.
- Confirm all project descriptions and skill claims are accurate and current.
- Test the live site on an actual iPhone/iPad and Android device, including a browser with WebGL disabled.

## Project structure

- `index.html` — scene, text fallback, case studies, styles and interactions.
- `favicon.svg` — browser tab icon.
- `social-preview.svg` — Open Graph / social preview artwork.

## Dependencies

- Three.js 0.160.0 (loaded from jsDelivr CDN).
- OrbitControls (included in the Three.js examples module).
