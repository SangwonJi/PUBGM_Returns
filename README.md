# DAU Heatmap Viewer

A fully client-side DAU (Daily Active Users) heatmap viewer — no server, no data upload, runs entirely in your browser.

## Features

- **4 views**: Monthly · Quarterly · Weekly · Daily (calendar heatmap)
- **Country filter** and top-N selection
- **Global / Per-country scale** toggle
- **Auto-detects** CSV encoding (UTF-16, UTF-8) and delimiter (tab, comma)
- Supports date formats: `YYYY. M. D.` · `YYYY-MM-DD` · `MM/DD/YYYY`

## CSV Format

| column  | description             |
|---------|-------------------------|
| date    | Date of record          |
| country | Country name            |
| DAU     | Daily Active Users count|

## GitHub Pages Setup

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Source: **Deploy from branch** → `main` → `/ (root)`
4. Your site: `https://<username>.github.io/<repo-name>/`

## Security

All data stays in your browser. Nothing is sent to any server.
