# 🌱 Pokémon Farm · 宝可梦农场

A self-contained browser farming game: grow crops, raise Ditto (百变怪), fish, forage,
and build your own Pokémon farm. Single HTML file, no build step, no server —
Three.js is loaded from public CDNs with fallbacks.

**Play it:** <https://slatinwine.github.io/pokemon-farm/>

## Run locally

Just open `index.html` in any modern browser. That's it.

## Deploy (GitHub Pages)

1. Repository → **Settings → Pages**
2. Source: **Deploy from a branch** → Branch: `main` / `/ (root)` → Save
3. The site goes live at `https://<user>.github.io/pokemon-farm/` within a minute or two.

## Tech

- Pure HTML / CSS / JavaScript (canvas 2D + Three.js 3D rendering)
- Save data persisted in `localStorage`, with export/import save codes
- Weather system, day/night cycle, fishing minigame, skills & shop
