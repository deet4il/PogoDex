# ⚡ Pokemon GO Tracker

**Created by: D.Aligaya**

A lightweight, responsive, and offline-ready Progressive Web App (PWA) designed for serious collectors to audit and track their **Pokémon GO Living Dex**, multi-form variants, and specialized specimens.

---

## 📱 Features & Capabilities

### 🎴 12 Collector Badges per Pokémon
Track every dimension of your collection on a single unified card:
- Standard Living Dex (`Caught`)
- ✨ `Shiny`
- 🍀 `Lucky`
- 🔥 `Shadow`
- ✨ `Purified`
- 💥 `Dynamax (D-Max)`
- ⚡ `Gigantamax (G-Max)`
- 💯 `100% IV (Hundo)`
- 0️⃣ `0% IV (Nundo)`
- 📏 `XXS Size`
- 📐 `XXL Size`
- 🎀 `Event / Costume`

---

### 🧬 Comprehensive Form & Variant Trackers
Dedicated, standalone cards with accurate sprites for all major collector sub-categories:
- **Regional Variants:** Alolan, Galarian, Hisuian, and Paldean forms.
- **Mega & Primal Evolutions:** Mega Charizard X/Y, Mega Rayquaza, Primal Groudon/Kyogre, Mega Lucario, and all released Megas.
- **Gender Differences (♂ / ♀):** Visual gender forms including Pyroar, Meowstic, Frillish, Jellicent, Indeedee, and Unfezant.
- **Unown Alphabet:** Complete 28-entry tracker (Letters A–Z, `!`, and `?`).
- **Spinda Patterns:** All 9 distinct spot patterns.
- **Furfrou Trims:** All 10 global trims (Natural, Heart, Star, Diamond, Debutante, Matron, Dandy, La Reine, Kabuki, Pharaoh).
- **Vivillon Wings:** All 18 postcard regional wing patterns (Icy Snow, Polar, Meadow, Marine, Sun, Ocean, Sandstorm, etc.).

---

### 🏆 Progress Medals & Gamification
Track milestones across individual regions and variant cohorts via the **🏆 Progress Medals** drawer:
- 🥉 **Bronze:** 50% Completion
- 🥈 **Silver:** 75% Completion
- 🥇 **Gold:** 90% Completion
- 💎 **Platinum:** 100% Master Completion

---

### 📷 In-Browser OCR Screenshot Scanner (Tesseract.js)
- Upload single or bulk screenshots of your in-game Pokémon GO storage.
- Client-side text recognition extracts Pokémon names using fuzzy matching (Levenshtein distance).
- Review matches in an interactive checklist and assign them to any category (e.g., bulk-check *✨ Shiny* or *💯 100% IV*) in one click.

---

### ⚡ Smart Evolutionary Cascade
- Enable **Auto-Cascade** to automatically mark prior evolution stages as caught when registering higher-tier evolutions (e.g., logging *Charizard* automatically checks *Charmander* and *Charmeleon*).

---

### 📊 Context-Aware Stats & Summary Inspection
- Real-time stat counters dynamically recalculate based on active filters and search terms (e.g., displays exact counts like `140 / 151 Shinies` for Kanto).
- **Interactive Badge Summaries:** Click any top dashboard badge to view a full modal checklist broken down by **All**, **Obtained (✓)**, and **Missing (✕)**.
- **Quick Copy:** Copy complete or missing specimen checklists directly to your clipboard for trade chats and hunting wishlists.

---

### 💾 Backup, Restore & Offline PWA
- **Local Data Storage:** All checklist progress is saved locally via `localStorage`.
- **JSON Import / Export:** Export timestamped backups and restore them across mobile and desktop devices.
- **Service Worker (Network-First Cache):** Fully functional offline with automated background updates when online.

---

## 🚀 Live Demo

Access the live web app directly on your browser or mobile device:  
`https://<YOUR-GITHUB-USERNAME>.github.io/<YOUR-REPO-NAME>/`

---

## 🛠️ Project Structure

```text
├── index.html        # App UI, state management, OCR engine, and database catalog
├── manifest.json     # Web App Manifest for mobile installation
├── sw.js             # Service Worker (v8 network-first cache & offline support)
├── icon-192.png      # 192x192 PWA app icon
├── icon-512.png      # 512x512 PWA splash & store icon
├── favicon.png       # 32x32 browser tab icon
└── README.md         # Repository documentation
