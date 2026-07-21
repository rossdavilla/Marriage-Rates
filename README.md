# Marriage Rates (1970–2025)

An interactive look at how the share of U.S. adults **ages 25–34** who are married
fell from **86 per 100** in 1970 to **34 per 100** in 2025.

## Pages

- **`index.html`** — the full page: hero, a static SVG trend chart, the "Pick a Year"
  spinner game, era cards (1970 / 1990 / 2025), and sources.
- **`pick-a-year-embed.html`** — a compact **720 × 450** version of just the spinner
  game, sized for embedding (e.g. in a Top Hat page) via an `<iframe>`.

## Embedding the game

```html
<iframe
  src="https://rossdavilla.github.io/Marriage-Rates/pick-a-year-embed.html"
  width="720" height="450" style="border:0"
  title="Would you be married?"></iframe>
```

## How the game works

Each spin is a random draw at the selected year's marriage rate (e.g. 86% in 1970,
34% in 2025). Spin repeatedly and the tally settles near the real rate — an
illustration of probability, not a prediction.

## Data

U.S. Census Bureau, "Living Arrangements" (2024) — share married among adults
ages 25–34, per 100. Values between labeled years are interpolated.
<https://www.census.gov/library/stories/2024/05/living-arrangements.html>

## Assets

Illustrations in `img/` are AI-generated in a flat-vector style and optimized for the web.
