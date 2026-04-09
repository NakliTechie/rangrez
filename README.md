# Rangrez

&#x26AB; **Try it now &rarr; https://rangrez.naklitechie.com**

A palette library of culturally-grounded color. Each palette is named after a tradition, place, craft, or moment, and tells a story about why those particular colors belong together.

Sibling project to **Kagaz**.

---

## What it does

- A browsable library of palettes organised by country, region, and theme
- Each palette tells a story &mdash; the history, material culture, or political moment behind the colors
- **Search** by palette name, story text, country, or hex code (try `saffron`, `cobalt`, or `#1a3a`)
- **Click any swatch** to copy the hex code straight to your clipboard
- **Export** any palette (or whole collection) as JSON &mdash; click for clipboard, Shift+click to download
- **Dark mode** with cream frames so dark-bodied palettes stay visible
- **Reader mode** on mobile, with prev/next navigation and inline stories
- Keyboard navigation: ⌘K / Ctrl+K to search, arrow keys to cycle palettes, Esc to close

## How to read it

Most country palettes follow a 4-role + 6-country structure:

- **LIGHT**, **WARM**, **MONO**, **DARK** roles
- Plus six culturally-distinctive country slots
- Each palette uses 7 slots: BODY, PANEL, INK, BRAND, ACT, OK, ROW

The slots aren't arbitrary &mdash; they trace specific places, dyes, materials, and (in several cases) political moments. Reading a country's colors means reading its arguments about itself.

## Tech

| Concern | Solution |
|---|---|
| Everything | Single HTML file &mdash; markup, styles, logic all inline |
| Dependencies | **Zero** |
| Build step | **None** &mdash; open `index.html`, it works |
| Privacy | Fully local. No server, no account, no tracking, nothing leaves the device |

## Licensing

This repo is dual-licensed:

- **Code / scaffolding** (HTML, CSS, JavaScript) &mdash; [MIT License](LICENSE)
- **Palette content** (palette names, color selections, prefaces, stories, all curatorial text) &mdash; [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE-content)

Both copyrights are held by Chirag Patnaik. If you reuse the content (palettes, stories), credit Chirag Patnaik and share your derivative under the same CC BY-SA 4.0 license. If you reuse just the code scaffolding, MIT terms apply.

## Part of the NakliTechie series

Browser-native tools &mdash; no server, no API keys, no data leaving the device.

| Tool | What it does |
|------|--------------|
| [**BabelLocal**](https://github.com/NakliTechie/BabelLocal) | Offline translation &mdash; 200 languages, NLLB model |
| [**StripLocal**](https://github.com/NakliTechie/StripLocal) | EXIF metadata stripper &mdash; nothing leaves the browser |
| [**GambitLocal**](https://github.com/NakliTechie/GambitLocal) | Chess vs Stockfish &mdash; correspondence mode via URL |
| [**VoiceVault**](https://github.com/NakliTechie/VoiceVault) | Audio transcription &mdash; Whisper, offline-first |
| [**KingMe**](https://github.com/NakliTechie/KingMe) | English draughts &mdash; custom minimax AI, zero deps |
| [**KoLocal**](https://github.com/NakliTechie/KoLocal) | Go (Baduk) &mdash; MCTS AI, zero deps |
| [**SnipLocal**](https://github.com/NakliTechie/SnipLocal) | Background remover &mdash; RMBG-1.4, passport mode |
| [**PredictionMarket**](https://github.com/NakliTechie/PredictionMarket) | Prediction market simulator &mdash; Parimutuel & LMSR |
| [**LocalMind**](https://github.com/NakliTechie/LocalMind) | Private AI chatbot &mdash; Gemma multimodal via WebGPU |
| **Rangrez** | Palette library &mdash; culturally-grounded color, single HTML file |

---

**Built by [Chirag Patnaik](https://github.com/NakliTechie)**
