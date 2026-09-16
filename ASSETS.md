### Asset verification

The project contains no broken raster-image imports. Visuals are intentionally local SVG assets so they work on `github.io` without external image-hosting failures:

- `assets/hero-network.svg` — hero connected-node illustration
- `assets/ai.svg` — reusable AI illustration
- `assets/cloud.svg` — reusable cloud illustration
- `assets.css` — local asset layer loaded after the main stylesheet

External Google Fonts and Font Awesome are enhancement-only dependencies; the CSS illustration remains visible if either CDN is unavailable.
