# ⚡ Pokémon GO Master Living Dex Tracker

A lightweight, responsive, and offline-capable Progressive Web App (PWA) designed to track and manage your **Pokémon GO Living Dex** and specialized collector variants.

---

## 📱 Features

- **10 Collector Categories per Pokémon:**
  - Standard Living Dex (`Caught`)
  - ✨ `Shiny`
  - 🍀 `Lucky`
  - 🔥 `Shadow`
  - ✨ `Purified`
  - 💯 `100% IV (Hundo)`
  - 0️⃣ `0% IV (Nundo)`
  - 📏 `XXS`
  - 📐 `XXL`
  - 🎀 `Event / Costume`
- **Dynamic Auto-Upgrade Engine:** Connects to live PokéAPI endpoints on startup to dynamically pull new species and future generations automatically.
- **pokemon.gameinfo.io Integration:** One-click links on every card to view move stats, weaknesses, and counter guides.
- **Cross-Device Backup & Restore:** Export your checklist data to a timestamped JSON file and restore it across phones, tablets, or desktop browsers.
- **Search & Filter Suite:** Fast filter controls by generation (Gen 1 through Gen 10+), collector status, and name/dex number search.
- **PWA & Offline Ready:** Includes a Service Worker (`sw.js`) and Web Manifest (`manifest.json`) for full offline availability and native home-screen installation.

---

## 🚀 Live Demo

You can access the live web app here:
`https://<YOUR-GITHUB-USERNAME>.github.io/<YOUR-REPO-NAME>/`

---

## 🛠️ Project Structure

```text
├── index.html        # Main app UI, state manager, and local storage engine
├── manifest.json     # Web App Manifest for mobile installation
├── sw.js             # Service Worker for offline asset caching
├── icon-192.png      # 192x192 PWA app icon
├── icon-512.png      # 512x512 PWA splash & store icon
├── favicon.png       # 32x32 browser tab icon
└── README.md         # Repository documentation
