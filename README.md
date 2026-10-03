# Color Palette Generator 🎨

Hit spacebar. Get a palette worth stealing.

**Day 8 · simple build of my daily coding journey** — I'm shipping one coding project every day. Follow the streak!

## Features

- 🎨 **5-color palettes** generated with one tap (or the spacebar)
- 🔒 **Lock your favorites** — locked colors survive every regenerate
- 📋 **Click any swatch to copy** its HEX code, with a "Copied!" pop-up
- 👁️ **Auto contrast text** — each swatch picks dark or light text based on luminance
- 📱 Responsive layout — swatches stack neatly on mobile

## Run it in 30 seconds

No build step, no dependencies. Just open the file:

1. Download or clone this repo
2. Open `index.html` in any browser
3. Press spacebar, done ✅

## What I practiced

- **Randomness** — `Math.random()` scaled to the 0–`0xFFFFFF` color range, converted with `.toString(16)`
- **Clipboard API** — `navigator.clipboard.writeText()` with a promise callback
- **Event listeners** — one `click` listener on the palette container that figures out *what* was clicked (event delegation)
- **DOM building** — creating swatches with `document.createElement` instead of hard-coding them
- Luminance math for picking readable text colors

## Try it

- Press <kbd>Space</kbd> three times — watch only unlocked colors change
- 🔒 the color you like best, then keep generating around it
- Click any swatch and paste the HEX into your design tool

---
Built with plain HTML, CSS & JavaScript. Day 8 of 365. 🚀
