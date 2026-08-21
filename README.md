# assets-2d-nature

2D nature-themed game assets (trees, terrain, water, animals, foliage)

## Stats

- **Total assets**: 1441
- **License**: CC0-1.0 (all Kenney assets are public domain)
- **Source**: [kenney.nl](https://kenney.nl)

## Source Packs

| Pack | Assets | License | Link |
|------|--------|---------|------|
| Kenney Background Elements | 127 | CC0-1.0 | [Link](https://kenney.nl/assets/background-elements) |
| Kenney Map Pack | 195 | CC0-1.0 | [Link](https://kenney.nl/assets/map-pack) |
| Kenney Platformer Art Deluxe | 983 | CC0-1.0 | [Link](https://kenney.nl/assets/platformer-art-deluxe) |
| Kenney Tiny Farm | 136 | CC0-1.0 | [Link](https://kenney.nl/assets/tiny-farm) |

## Structure

```
assets-2d-nature/
├── assets/kenney/    # Organized by source pack
├── previews/         # Pack preview images
├── LICENSES/         # License files per pack
├── manifest.json     # Machine-readable asset index (1441 entries)
├── tags.json         # Genre, theme, style tags
└── README.md
```

## Usage

Browse `manifest.json` for the full asset index. Each entry includes:

```json
{
  "id": "kenney-<pack>/<asset-name>",
  "name": "Human Readable Name",
  "path": "assets/kenney/<pack>/...",
  "source": "Kenney <Pack Name>",
  "sourceUrl": "https://kenney.nl/assets/<pack>",
  "license": "CC0-1.0",
  "tags": [...],
  "fileType": "png|ogg|obj|..."
}
```

## License

All assets are **CC0-1.0** (Creative Commons Zero) — public domain, free for any use including commercial, no attribution required. See `LICENSES/` for original license files from each pack.
