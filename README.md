# Dashboard

Static HTML version of my Notion "🏠 Dashboard" page: clock, weather, Windy wind map, AirNav Radar, and two YouTube live streams.

## Host on GitHub Pages

1. Create a new repo (e.g. `dashboard`) and push `index.html`, `.nojekyll`, and this README to the `main` branch root.
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
3. After a minute it's live at `https://<your-username>.github.io/dashboard/`.

No build step or dependencies — it's a single static file.

## Editing

Each embed is an `<iframe>` in `index.html`. To change heights, edit `.h-widget` (clock/weather) and `.h-map` (Windy/AirNav) in the `<style>` block.
