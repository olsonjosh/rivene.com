# Rivene App Icon

This folder preserves the selected faceted inset app icon treatment.

## Selected Direction

- Cool glass surface with a soft light-to-dark gradient, visible specular shine,
  and subtle prismatic tinting. Avoid a flat matte tile.
- Graphite lightning cutout using the canonical Rivene mark geometry.
- Inset/debossed bolt lighting only: no outside cast shadow around the bolt.
- Faceted center shadow where the two triangles meet. This is intentional; it should feel like the surface is splitting open rather than like a flat glyph.
- iOS/watchOS app icon exports must remain square, fully opaque PNGs. Let the
  system apply the rounded mask.

## Files

- `rivene-app-icon-faceted-inset-1024.png` is the master app icon image.
- `rivene-app-icon-faceted-inset-512.png` is a large preview/export.
- `rivene-app-icon-faceted-inset-256.png` is a medium preview/export.
- `rivene-app-icon-faceted-inset-192.png` is the web app manifest icon.
- `rivene-app-icon-faceted-inset-180.png` is the Apple touch icon.
- `rivene-app-icon-faceted-inset-128.png` is a small preview/export.
- `rivene-app-icon-faceted-inset-64.png` is a compact preview/export.
- `rivene-app-icon-faceted-inset-32.png` is the smallest legibility check.

The `rivene-app-icon-faceted-inset-glass-*.png` files preserve the same opaque
shiny glass master and canonical bolt artwork for website presentation.

The iOS and watchOS asset catalogs should use the 1024px master image unless the icon direction changes.
