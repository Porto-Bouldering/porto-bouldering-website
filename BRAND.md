# Porto Bouldering — brand guide

Quick reference for colours, type, imagery and voice, so new pages, posts and merch stay consistent.

## Name and contacts

- **Name:** Porto Bouldering (always two words; set in capitals in logos: `PORTO BOULDERING`)
- **Website:** https://portobouldering.pt
- **Instagram:** [@portobouldering](https://www.instagram.com/portobouldering/)
- **Email:** portobouldering@gmail.com
- **Language:** Portuguese (pt-PT) first.

## Colours

### Core palette

| Name | Hex | Use |
|---|---|---|
| Castanho Raiz | `#2D1F18` | Main background (website), dark merch colour |
| Creme | `#F1E3C8` | Main text and prints on dark backgrounds |
| Creme suave | `#CDB99A` | Secondary text (taglines, contacts) |
| Preto | `#000000` | Logo and illustrations on light backgrounds |
| Branco | `#FFFFFF` | Logo and illustrations on dark backgrounds |

### Merch colours ("Ghost House" collection)

| Name | Hex |
|---|---|
| Azul Granito | `#3F5965` |
| Castanho Raiz | `#2D1F18` |
| Verde Líquen | `#6D7654` |
| Areia (sand t-shirt) | approx. `#E8DCC8`, taken from the mockup, so check it against the real fabric |

Prints on the merch colours are in Creme (`#F1E3C8`). On the sand t-shirt, prints are black.

### Website background helpers

| Hex | Use |
|---|---|
| `#3A2A20` | Soft lighter glow behind the centre content |
| `#1F150F` | Darker edges (vignette) |

## Typography

| Role | Font | Notes |
|---|---|---|
| Headlines | **Archivo Black** ([Google Fonts](https://fonts.google.com/specimen/Archivo+Black)) | Uppercase, tight letter-spacing (`-0.01em`). Closest web match to the logo wordmark. |
| Body, labels, small caps | **Archivo** 500–600 ([Google Fonts](https://fonts.google.com/specimen/Archivo)) | For taglines and labels: uppercase with wide letter-spacing (`0.12em`–`0.35em`). |
| Fallbacks | `"Arial Black", Impact, sans-serif` for headlines; `"Helvetica Neue", Arial, sans-serif` for body | |

Other lettering seen in the brand:
- **Merch prints** ("PORTO / BOULDERING" arched, "NUTS FOR BOULDERING") use a soft, rounded, retro bold serif in the style of Cooper Black. It isn't on Google Fonts, so it's for print and illustration only.
- **Hand-drawn lettering**: jagged, irregular brush capitals in the sketch artwork. Use it in illustrations, never set it as web text.

Google Fonts link used on the site:

```html
<link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Archivo:wght@500;600&display=swap" rel="stylesheet" />
```

## Logo and mascot

- **Mascot: the ghost.** A friendly white ghost carrying a crash pad on its back, holding a toothbrush (for brushing holds) and making a shaka hand sign. Bold black outline, cartoon style.
- **Logo variants:**
  - Ghost + `PORTO BOULDERING` wordmark, black on white.
  - The same, white on black.
  - Ghost on its own, with no text. Use it for icons, avatars and small spaces.
- **Wordmark:** `PORTO` / `BOULDERING` stacked on two lines, left-aligned, heavy geometric sans, with the ghost to the upper right.
- **Clear space (suggested):** keep at least the height of the "O" in PORTO free around the logo.
- **Avoid (suggested):** recolouring the ghost, stretching it, adding effects (shadows, glows, gradients), or putting the black version on dark backgrounds.

## Imagery and illustration style

- **Line art:** black ink, thick confident outlines, flat fills, very little shading. Playful and cartoonish.
- **Recurring scenes:** the ghost at a Porto bus stop, the ghost on a boulder with a small house on top ("Ghost House"), the ghost carrying a crash pad.
- **Topo-map style** (used as the website's background texture):
  - Boulders are solid flat shapes with flat sides and rounded corners, separated by thin gaps.
  - Problems are numbered, with small arrows pointing to their start.
  - Sectors are labelled in condensed capitals (for example `SECTOR CORVO`).
  - A single curved line marks the trail or path.
  - On dark backgrounds, draw the shapes in Creme at about 5–6% opacity so they stay a subtle texture.

## Voice and taglines

- Short, casual, a bit cheeky. Climbing in-jokes are welcome.
- Portuguese first; English is fine for merch slogans.
- Taglines and phrases in use:
  - "Feito de pedra." (website tagline)
  - "Brevemente" (coming-soon page)
  - "Que cor vais vestir?" (merch launch)
  - "Nuts for bouldering"
  - "This t-shirt will be covered in chalk…"
  - Merch collection name: **Ghost House**

## Website assets (in this repo)

| File | What it is |
|---|---|
| `assets/boulders.svg` | Background texture for wide screens (topo-map boulders + trail) |
| `assets/boulders-portrait.svg` | Same texture laid out for phones (portrait) |
| `assets/favicon.ico`, `assets/favicon-16.png`, `assets/favicon-32.png` | Browser tab icons (ghost only, transparent background) |
| `assets/apple-touch-icon.png` | Home-screen icon for iPhone/iPad (ghost on Creme `#F1E3C8`) |

### CSS starter

```css
:root {
  --castanho-raiz: #2d1f18;
  --creme: #f1e3c8;
  --creme-suave: #cdb99a;
  --azul-granito: #3f5965;
  --verde-liquen: #6d7654;
  --font-headline: "Archivo Black", "Arial Black", Impact, sans-serif;
  --font-body: "Archivo", "Helvetica Neue", Arial, sans-serif;
}
```
