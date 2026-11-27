# eccormerce — Try the Look

A standalone "Try the Look" runway page for an e-commerce storefront. Shoppers browse six head-to-toe looks, tap numbered pins to see each piece, and add single items or the full look to a styling bag.

## Features

- **Runway carousel** — swipe, drag, or use the arrow keys to move between looks; optional autoplay with progress ticks.
- **Shoppable pins** — each look has numbered hotspots linked to its product cards.
- **Zoom view** — open a look full screen and tap a dot to shop that piece.
- **Size picker** — choose a size before adding a product to the bag.
- **Bundle pricing** — "Complete the look" adds every piece at 10% off; prices and piece counts are computed from each look's products.
- **Styling bag** — saved in `localStorage`, so it survives a page reload.
- **Accessible** — keyboard navigation, ARIA labels, and live-region announcements.

## Project structure

```
index.html        # Site root served on Vercel
runway/
└── index.html    # Runway page: markup, styles, and scripts in one file
vercel.json       # Vercel config (plain static site from the repo root)
```

Deployed on Vercel as a static site.

## Running locally

No build step or dependencies. Open `runway/index.html` in a browser, or serve the folder:

```bash
npx serve runway
```

## Tech

Plain HTML, CSS, and vanilla JavaScript (custom elements). No frameworks.

## Author

Adekola Timothy — [@TTech-spec](https://github.com/TTech-spec)
