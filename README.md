# Mekong Quay — Development Layer Viewer

Interactive visualization of urban development layers for the Mekong Quay site in Phnom Penh, based on data from the [Build4People Project](https://www.build4people.org/) (WP5 Urban Planning).

## Live Demo

Open `mekong_quay_viewer.html` in any modern browser — no server or dependencies required.

## What it shows

Six planning layers for the Mekong Quay development site, each highlighting a different aspect of the urban design:

| Layer | Theme |
|-------|-------|
| 1 | Green & Open Space |
| 2 | Water Management |
| 3 | Wind Corridors |
| 4 | Street Network |
| 5 | Land Use Zones |
| 6 | Mobility & Transport |

The layers share a common aerial base map and can be viewed individually, blended into each other, or cycled through as an animation.

## Views

Three preset groups are available via the tab bar:

- **Layers 1–3** — Environmental systems (green space, water, wind)
- **Layers 4–6** — Urban infrastructure (streets, zoning, mobility)
- **All Layers** — Complete overview of all six layers

Switch views with the tabs or press `1`, `2`, `3` on the keyboard.

## Controls

| Control | Function |
|---------|----------|
| **Auto** | Automatic crossfade slideshow between layers |
| **Manual** | Navigate layers by clicking dots or using arrow keys |
| **Blend** | Continuous slider to smoothly blend between adjacent layers |
| **Fast / Normal / Slow** | Adjusts auto-play interval (2s / 4s / 7s) |

### Keyboard shortcuts

| Key | Action |
|-----|--------|
| `←` `→` | Previous / next layer |
| `Space` | Next layer |
| `1` `2` `3` | Switch to Layers 1–3 / 4–6 / All |

## Technical details

- Single self-contained HTML file (~1.1 MB), no external dependencies
- All six layer images embedded as Base64 JPEG (1600 × 952 px each)
- Build4People logo embedded as Base64 PNG
- Smooth CSS transitions with `cubic-bezier` easing for crossfades
- Blend mode uses direct opacity interpolation for seamless layer mixing
- Google Fonts loaded externally: Outfit (UI text), IBM Plex Mono (labels/controls)

## Data sources

- Layer maps: Build4People Project, WP5 Urban Planning
- Aerial base imagery: Phnom Penh metropolitan area

## License

Map data and planning layers © Build4People Project. This visualization is provided for research and educational purposes.
