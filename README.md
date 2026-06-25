# Sprite Sheet to GIF Converter

A free web tool that converts sprite sheets into animated GIFs. Useful for game developers and animators.

**Use it here: [https://ironexcavater.github.io/spritesheet-to-gif](https://ironexcavater.github.io/spritesheet-to-gif)**

## Features

- Upload any sprite sheet image, including via drag-and-drop
- Configure rows and columns to extract frames
- Crop margins with offset controls before slicing frames
- Adjust frame delay (animation speed) and encoding quality
- Choose whether the GIF loops forever or plays once
- Transparent areas in the source PNG are preserved as a transparent background in the generated GIF, or filled with a custom background color
- Download the generated GIF
- Runs entirely in the browser — no upload to a server, no account, no paywall

## Technologies

- Pure HTML, CSS, and JavaScript — no build step
- Uses [gif.js](https://github.com/jnordberg/gif.js) by Johan Nordberg for GIF encoding

## Running locally

```bash
git clone https://github.com/IronExcavater/spritesheet-to-gif.git
cd spritesheet-to-gif
npm install
npm run dev
```

This serves the folder at `http://localhost:3000`. You can also skip npm entirely and just open `index.html` directly in a browser, or serve the folder with any static file server.

In VS Code, run the **Run Sprite Sheet to GIF** launch configuration. It starts `npm run dev` automatically and opens Chrome with source debugging enabled.

## Scripts

- `npm run dev` — serve the site locally at `http://localhost:3000`
- `npm run format` — format HTML/CSS/JS with Prettier
- `npm run format:check` — check formatting without writing (used in CI)

## Deployment

Pushes to `main` are automatically deployed to GitHub Pages via [.github/workflows/deploy.yml](.github/workflows/deploy.yml). Pull requests and pushes also run a formatting check via [.github/workflows/ci.yml](.github/workflows/ci.yml).

## License

MIT — see [LICENSE](LICENSE).
