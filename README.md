# Personal Portfolio

It's built with plain HTML, modern CSS (SCSS source), and small JavaScript enhancements for animations and interactivity.

--

## Features

- Clean, responsive design optimized for desktop and mobile.
- Sectioned layout: hero, about, projects, and contact.
- SCSS source with organized partials for easy theming and reuse.
- Small JS utilities for scroll reveal and tilt animations.

## Technologies

- HTML5
- SCSS (Sass) — source available in `src/sass/`
- JavaScript (vanilla) — `src/scripts/`
- Optional: any static file server for previewing (see Getting Started)

## Project Structure

- `index.html` — main entry page
- `index.js` — main JavaScript file
- `styles.scss` — primary Sass file (compiled CSS output lives beside it during development)
- `assets/` — images, icons and other static assets
- `src/sass/` — SCSS partials and organized styles (abstracts, base, components, layout, sections, vendors)
- `src/scripts/` — small JS modules like `scrollReveal.js` and `tiltAnimation.js`

## Getting Started

To preview the portfolio locally, you have several simple options:

1. Open the `index.html` file directly in your browser (works for static prototypes).

2. Use VS Code Live Server: install the Live Server extension and click "Go Live".

3. Use a tiny static server via npm (recommended):

```bash
# from the project root
# install a simple static server once (if you don't have one)
npx serve .

# or use http-server
npx http-server .
```

Then open the address shown by the tool (usually `http://localhost:3000` or similar).

## Development

- SCSS: If you edit SCSS, compile it to CSS. If you have `sass` installed globally:

```bash
# watch & compile
sass --watch src/styles.scss:styles.css
```

- JS: The project uses vanilla JS modules in `src/scripts/`. Edit them directly and refresh the page.

## Deployment

This is a static site — you can host it on GitHub Pages, Netlify, Vercel, or any static hosting provider. General steps:

- Push the repository to GitHub and enable GitHub Pages from the repository settings, or
- Drag & drop the `index.html` and `assets/` folder into Netlify/Vercel or connect your repo for automatic deploys.

## Customize

- Colors, spacing, and variables are in `src/sass/abstracts/_variables.scss`.
- Add or remove sections by editing `index.html` and the corresponding SCSS partial in `src/sass/sections/`.

## Contributing

Contributions are welcome. For bug fixes or enhancements:

1. Fork the repository.
2. Create a topic branch (`git checkout -b feat/my-change`).
3. Commit your changes and open a pull request.

## License

Check the `LICENSE.md` file in the project root for licensing details.

## Contact

If you'd like to reach out or request customization, add your contact details or link to your social profiles here.

--
