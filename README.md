<div align="center">

# 📊 DAU Heatmap Viewer

**A fully client-side Daily Active Users heatmap — no server, no data stored, runs entirely in your browser.**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)](https://SangwonJi.github.io/PUBGM_Returns/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#)
[![No Server](https://img.shields.io/badge/Server-None-lightgrey)](#)
[![Language](https://img.shields.io/badge/Lang-EN%20%2F%20한-orange)](#)

</div>

---

## ✨ Features

| | Feature |
|---|---|
| 🗓️ | **4 time views** — Daily · Weekly · Monthly · Quarterly |
| 🌍 | **Country filter** — Global aggregate or per-country breakdown |
| 🎨 | **2 color modes** — % Change (green/red) or Absolute DAU intensity |
| 🇰🇷 🇺🇸 | **Bilingual UI** — Toggle between Korean / English |
| 📐 | **CoinGlass-style layout** — Rows = Years, Cols = Periods, Average + Median rows |
| ⚡ | **Fast parsing** — Chunked processing for large CSVs (600K+ rows) |
| 🔐 | **Privacy-first** — All data stays in your browser, zero uploads |

---

## 📁 CSV Format

```
date          country    DAU
2024. 1. 1.   KR         1500000
2024. 1. 1.   US         3200000
```

| Column | Description | Supported Formats |
|--------|-------------|-------------------|
| `date` | Date of record | `YYYY. M. D.` · `YYYY-MM-DD` · `MM/DD/YYYY` |
| `country` | Country name or code | Any string |
| `DAU` | Daily Active Users | Integer |

> Auto-detects encoding (**UTF-16 LE/BE**, **UTF-8**) and delimiter (**tab**, **comma**)

---

## 🚀 GitHub Pages Setup

```bash
# 1. Clone or push this repo to GitHub
git push origin main

# 2. Enable GitHub Pages
# Settings → Pages → Branch: main / (root) → Save

# 3. Access your live site
# https://<username>.github.io/<repo-name>/
```

---

## 🔒 Privacy & Security

```
Your CSV data never leaves your device.
No analytics. No cookies. No server.
```

All processing happens in-browser via JavaScript — the file is read into memory,
rendered as a heatmap, and discarded when you close the tab.

---

<div align="center">

Made with ♥ for PUBGM Analytics

</div>
