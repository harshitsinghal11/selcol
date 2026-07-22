# Color Theory — A Working Reference

An interactive, single-file color tool. Drag one wheel to set a base hue, and everything a real project needs — tints, shades, harmonies, a full UI palette, gradients, dark mode, and exportable code — is generated live from that one color.

No build step, no dependencies. Open `color-theory-guide.html` in a browser and it just works.

## Features

- **Color wheel** — drag to set hue, with saturation/lightness sliders
- **Tints, shades & tones** — six-step strips generated from the base color
- **Harmonies** — complementary, analogous, split-complementary, triadic, tetradic, monochromatic
- **60/30/10 rule** — dominant / secondary / accent ratio preview
- **Automatic UI palette** — background, surface, borders, text, buttons (incl. hover/active/disabled), links, focus rings, and status colors (success/warning/error/info), all derived from the base hue
- **Light / dark mode toggle** — a properly built dark variant, not just an inverted one
- **Live mock UI** — the generated palette applied to a real card, button, badges, and input
- **Elevation scale** — sm → xl tinted shadows for consistent depth
- **Gradients** — brand, accent, button, and overlay/scrim presets built from the palette
- **Export** — copy-ready CSS custom properties and a Tailwind config, both light and dark

## Tech

Plain HTML, CSS, and vanilla JavaScript. All color math (HSL ↔ hex/RGB, mixing, contrast ratios) is done in a few small functions with no external libraries. Fonts are loaded from Google Fonts; everything else works offline.

## License

MIT — use it, fork it, ship it.
