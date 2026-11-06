# La Hacienda Authentic Mexican Restaurant

Single-page website for La Hacienda — 1370 S Glenstone Ave, Springfield, MO.

Unofficial sample site. Details come from public listings and may be out of date.
Not affiliated with the restaurant.

## Stack

Plain HTML, CSS and a little vanilla JavaScript. No build step, no dependencies.

## Local preview

Double-click `index.html` to open it in your browser.

## Deploy on Vercel

1. Go to [vercel.com/new](https://vercel.com/new).
2. Import this GitHub repository.
3. Framework preset: **Other**. Build command: none. Output directory: `.`
4. Deploy.

Vercel serves `index.html` from the root automatically, so no configuration file is needed.

## Editing

Everything lives in `index.html`:

- Address, phone and hours are in the hero, "Come hungry" section and footer.
- Colors are CSS variables in `:root` (`--ink`, `--sun`, `--rose`, `--chili`).
- The colored paper flags at the top are generated from `.flags i` elements; six colors cycle.
- On phones, a fixed call/directions bar appears at the bottom.
