# Home Style Theme

A calm Home Assistant theme inspired by Apple's design: rounded inset cards, soft system colours,
large titles, hairline separators and a gentle background gradient.

The file holds two themes:

- **Home Style**: frosted white glass in light mode; solid graphite cards (#1C1C1E) on a darker
  background in dark mode, with no blur and no edge reflections.
- **Home Style Lite**: the same without blur, for wall tablets and older devices.

Both follow the device's light or dark mode.

It is built on [Frosted Glass](https://github.com/wessamlauf/homeassistant-frosted-glass-themes) by
Wessam Lauf (MIT): his file merged with an overlay of changes (corner radii, no borders, state
colours, dark mode).

Goes with [Home Style Cards](https://github.com/falcon2k16/home-style-cards), which read the theme's
`--home-style-fill`, `--home-style-separator` and `--ha-card-glass-tint` variables and render in their
final look on the first frame.

## Install

1. Home Assistant needs themes enabled (`frontend: themes: !include_dir_merge_named themes` in
   `configuration.yaml`).
2. Open **Settings → Marketplace** and add this repository's URL as a custom repository of the
   type **Theme** (this needs the Marketplace's GitHub connection).
3. Install **Home Style Theme**, then run the `frontend.reload_themes` action.
4. Pick **Home Style** in your profile, or set it per dashboard view.

Requires Home Assistant 2026.11 or newer.

## License

MIT. Includes Frosted Glass, © 2025 Wessam Lauf, under the MIT license.
