# imageworks-hero

Custom hero page built for **imageworks Creative** — _Website + Marketing Built to Work Together._

A static landing-page hero with an animated Lottie gradient background, a floating sphere/gear motif, the imageworks brand wordmark in the nav, and an interactive service-node diagram (Initial Build / Ongoing) around a rotating center graphic.

## Stack

- Plain HTML + CSS (no build step)
- [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- [`lottie-web`](https://github.com/airbnb/lottie-web) (CDN) for the animated gradient
- Inline SVG for the diagram connectors and node icons
- `center.svg` pulled live from [`sraponte91/iwc-web-market`](https://github.com/sraponte91/iwc-web-market)

## Run

Open `hero.html` directly in any modern browser — no server required. First load needs an internet connection (Google Fonts, lottie-web CDN, the remote `center.svg`).

## Files

| File | Purpose |
|---|---|
| `hero.html` | The whole page (HTML + CSS + JS inline) |
| `imageworks-logo.png.png` | Brand wordmark used in the nav |
| `sphere.png`, `gear.png` | Floating decorative elements around the headline |
| `gradient-background.json` | Source Lottie data (inlined into `hero.html`) |
