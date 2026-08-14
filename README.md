# Pokopla — The Pokopia Planning Tool

[🇩🇪 Deutsch](./README.md) · 🇬🇧 English

An unofficial, browser-based planning tool for **Pokémon Pokopia**. Use it to organize your Pokémon into custom groups, assign habitats, and keep track of abilities and litter items — runs entirely in your browser, no sign-up, no server, your data stays on your device.

**[→ Live demo](https://bwons.github.io/Pokopla/)**

---

## Features

- Complete Pokopia Pokédex database (base game, Bubbly Basin DLC, event Pokémon) with abilities and litter items
- Custom groups with color, description, and WIP/DONE status
- Habitat management, including your own renamed/custom areas
- Drag & drop, bulk actions, an edit mode with Discard/Save
- Bilingual (German/English), including translated Pokémon names, abilities, and area names
- Installable as a Progressive Web App (PWA) — works offline, own app icon on iOS and macOS
- JSON export/import for backups and transferring data between devices

## Usage

Just open `index.html` in your browser, or host the whole repo via GitHub Pages (Settings → Pages → Deploy from branch → `main` / `root`). All paths are relative, so it works whether it's served from `username.github.io` or `username.github.io/repo-name`.

**Installing as an "app":**
- iPhone: Safari → Share → "Add to Home Screen"
- Mac (Sonoma+): Safari → File → "Add to Dock"

## How this tool came to be

This tool was built largely with the help of **Claude (Anthropic)** — from the basic structure through individual features to researching the Pokémon data. The full source is open in this repository, so anyone can see exactly what it does (no tracking, no hidden data transmission — see [Privacy](#privacy)).

## Data sources

The Pokémon, ability, and habitat data comes from publicly available community wikis, primarily:
- [bisafans.de](https://www.bisafans.de/spiele/spin-offs/pokopia/) (German names, abilities)
- [Serebii.net](https://www.serebii.net/pokemonpokopia/) (English ability reference)

All data was researched to the best of my knowledge, but comes with no guarantee of completeness or accuracy — Pokopia is continuously updated and expanded.

## Privacy

This tool collects no data whatsoever, has no tracking and no analytics. Everything you enter (groups, assignments, custom Pokémon) is stored exclusively in your browser's local `localStorage` and never leaves your device — unless you export it yourself as a JSON file. There is no communication with any server (other than the one-time loading of the app files themselves).

## Legal / Disclaimer

**Pokémon, Pokopia, and all related names, characters, and images are trademarks and copyrights of Nintendo, Creatures Inc., and GAME FREAK inc.** This project is an unofficial fan tool with no affiliation to Nintendo, The Pokémon Company, Creatures Inc., or GAME FREAK inc., and is not endorsed or authorized by them in any way. It is intended solely for private, non-commercial use.

No copyright is claimed over Pokémon names, abilities, or other in-game data — these remain the property of their respective rights holders. Copyright is claimed only over the source code written for this tool (see [LICENSE](./LICENSE)).

If you are a rights holder and have concerns about this project, please open an issue or contact me directly — I will take the repository down promptly.

## License

The source code of this tool is licensed under [CC BY-NC 4.0](./LICENSE) (Attribution, NonCommercial) — you're free to use, modify, and redistribute it, but not commercially. This license does **not** cover Pokémon-related names, data, or trademarks (see above).
