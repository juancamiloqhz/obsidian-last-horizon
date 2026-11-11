# Last Horizon

An Obsidian theme ported from the [Omarchy](https://omarchy.org) **Last Horizon** theme: near-black surfaces, warm off-white text and a dusty-rose accent. Ships a dark scheme (faithful to the original palette) and a derived light scheme.

## Palette (dark)

| Role | Color |
| --- | --- |
| Background | `#0c0b0c` |
| Sidebar / ribbon | `#090809` |
| Text | `#e2dddc` |
| Accent | `#b59790` |
| Muted | `#584e51` |
| Cyan / Green / Magenta / Red | `#a5a0b6` / `#87a9b0` / `#c4d8e2` / `#c38b7b` |

## Features

- Dark and light schemes
- Accent color configurable through the [Style Settings](https://github.com/obsidian-community/obsidian-style-settings) plugin
- Code blocks use `FiraCode Nerd Font Mono` when installed, with fallbacks

## Install

After approval: **Settings → Appearance → Themes → Manage → Last Horizon**.

Manually: copy `theme.css` and `manifest.json` into `<vault>/.obsidian/themes/Last Horizon/`.

## Development

```sh
npm install
npm run lint
```

Release: bump `version` in `manifest.json` (and `versions.json`), then push a matching tag. The workflow creates a draft GitHub release with `manifest.json` and `theme.css`.

## License

MIT
