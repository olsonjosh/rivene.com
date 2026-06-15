# rivene brand assets

This folder contains reusable rivene logo assets based on the selected Clear Edge lightning mark.

## Shape Source Of Truth

The canonical mark path is:

```svg
M50 12 L96 69 H68 L76 114 L30 57 H58 Z
```

Use this path when generating new SVG exports so color, shadows, or app-icon surfaces can change without changing the mark geometry.

## Files

- `rivene-mark.svg` is the plain vector mark. It uses `currentColor` through `--rivene-mark-color` when embedded inline.
- `rivene-mark-clear-edge.svg` is the selected material version with the Clear Edge relief.
- `rivene-lockup.svg` combines the material mark, lowercase `rivene`, and `lightning log` descriptor.
- `rivene-logo.css` contains a CSS-only mark using the same normalized polygon points, plus icon and lockup helper classes.
- `app-icon/` preserves the selected faceted inset app icon as a 1024px master plus smaller preview exports.

## CSS-Only Example

```html
<link rel="stylesheet" href="/brand/rivene-logo.css">

<div class="rivene-logo-css" style="--rivene-mark-color:#cad2db">
  <span class="rivene-icon-css">
    <span class="rivene-mark-css rivene-mark-css--clear-edge"></span>
  </span>
  <span class="rivene-logo-css__text">
    <span class="rivene-logo-css__name">rivene</span>
    <span class="rivene-logo-css__descriptor">lightning log</span>
  </span>
</div>
```

For a flat one-color mark:

```html
<span class="rivene-mark-css" style="--rivene-mark-size:32px; --rivene-mark-color:#1d1d1f"></span>
```
