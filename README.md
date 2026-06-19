# Sprite Sheet to GIF Converter

A free web tool that converts sprite sheets into animated GIFs. Useful for game developers and animators.

**Use it here: [https://ironexcavater.github.io/spritesheet-to-gif](https://ironexcavater.github.io/spritesheet-to-gif)**

<img src="assets/siteOGImage.png" width="400" alt="Sprite Sheet to GIF Converter screenshot">
<img src="assets/sprite-animation.gif" width="200" alt="Example animated GIF output">

## Features

- Upload any sprite sheet image
- Configure rows and columns to extract frames
- Crop margins with offset controls before slicing frames
- Adjust frame delay (animation speed)
- Transparent areas in the source PNG are preserved as a transparent background in the generated GIF
- Download the generated GIF
- Runs entirely in the browser — no upload to a server, no account, no paywall

## Technologies

- Pure HTML, CSS, and JavaScript — no build step
- Uses [gif.js](https://github.com/jnordberg/gif.js) by Johan Nordberg for GIF encoding

## Running locally

```bash
git clone https://github.com/IronExcavater/spritesheet-to-gif.git
cd spritesheet-to-gif
```

Then open `index.html` directly in a browser, or serve the folder with any static file server.

## License

MIT — see [LICENSE](LICENSE).
