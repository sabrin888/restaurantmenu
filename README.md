# Dum & Spice — Restaurant Menu

A responsive restaurant menu inspired by the supplied biryani design video. Warm ivory, saffron yellow, lavender cards, oversized typography, and a horizontal dish carousel.

## Run locally

No dependencies or build step required. Serve the `dist` folder:

```bash
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000.

## Features

- Mobile and desktop layouts
- Category filters and scrollable menu
- Order basket with quantity controls and browser-local persistence
- Copyable order summary, with manual-copy fallback
- Keyboard accessible controls, modal, and reduced-motion support

This is a frontend demonstration using sample branding, dishes and INR prices. It does not submit orders or accept payments. Change the `menu` array in `dist/app.js` to edit dishes and prices. Replace the images in `dist/assets` to customize photography. Hero copy is in `dist/index.html`; visual styles are in `dist/style.css`.

## Assets

Food photography generated for this project using the built-in image generation tool. Font families are loaded from Google Fonts with system fallbacks. No customer reviews or business details are represented as verified facts.
