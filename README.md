# Hockey Hub — COMP 584 Project 2

A responsive hockey-themed page built with HTML and CSS Flexbox.

**Live site:** https://eli-cub.github.io/comp584-project2/

## Layout
- **Row 1:** Four single-column cards on desktop.
- **Row 2:** Two cards spanning two columns each.
- **Row 3:** A one-column card next to a three-column feature.
- **Row 4:** One card spanning all four columns.
- **Row 5:** One-column / two-column / one-column. The middle card is displayed first on tablet and mobile using CSS `order`.
- **Row 6:** Five equal-width cards on desktop, a different layout from the other rows.

The grid uses `display: flex`, `flex-flow: row wrap`, `flex-basis`, and media queries at **480px** and **768px**.

## How to view locally
Open `index.html` in a browser, or use the VS Code Live Server extension.

## Photo credits
Hockey images are loaded from [Unsplash](https://unsplash.com/s/photos/ice-hockey).

## GitHub Pages
Publish this repository from **Settings → Pages → Deploy from a branch → main → /(root)**.
