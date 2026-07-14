# DEAD GRID: INFINITE NIGHT

### 🧟 Human vs Zombie Survival — A Neon Top-Down Shooter Built for the Browser

*Endless waves, one glowing grid, zero installs.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Made with HTML5 Canvas](https://img.shields.io/badge/Made%20with-HTML5%20Canvas-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg)](index.html)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange.svg)](CONTRIBUTING.md)

[🎮 Play Now](#-quick-start) · [📖 How to Play](#-controls) · [🐛 Report Bug](../../issues/new?template=bug_report.md) · [💡 Request Feature](../../issues/new?template=feature_request.md)

---

## 📌 Why Dead Grid?

Most browser shooters need a build step, a bundler, or a dozen npm packages before you even see a pixel. **Dead Grid: Infinite Night** doesn't.

It's a single self-contained `index.html` — HTML, CSS, and JavaScript all in one file — that renders a fully lit, particle-driven, top-down zombie survival arena straight from the Canvas 2D API. Open it, and you're already inside the grid.

### ✨ What Sets This Apart

| Feature | Description |
|---|---|
| 🕹️ **Zero-install** | One HTML file. No build tools, no bundlers, no server required |
| 📱 **Mobile-ready** | Virtual joystick + fire button auto-appear on touch devices |
| 🎨 **Living arena** | Dynamic player-following light, ambient drifting dust, animated scanlines |
| 💀 **Persistent gore** | Every zombie kill leaves a permanent blood decal on the floor |
| 🔫 **Auto-aim combat** | Shooting locks onto the nearest zombie, with muzzle flash, shell casings, and gib particles |
| 🏆 **High score memory** | Best score is saved locally in your browser between sessions |
| ⚡ **Rising difficulty** | Zombies spawn faster and hit harder the longer you survive |

---

## 🚀 Quick Start

### Option 1 — Play Instantly (Recommended)

👉 Just open **`index.html`** in any modern browser. No setup required.

### Option 2 — Clone & Run Locally

```bash
# Clone the repository
git clone https://github.com/<your-username>/Dead-Grid-Infinite-Night.git
cd Dead-Grid-Infinite-Night

# Open the game — no server, no install
open index.html      # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

### Option 3 — Host on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Set the source branch to `main`, folder `/ (root)`.
4. Play it live at `https://<your-username>.github.io/Dead-Grid-Infinite-Night/`.

---

## 🎮 Controls

| Action | Desktop | Mobile |
|---|---|---|
| Move | `W` `A` `S` `D` | Virtual joystick (bottom-left) |
| Shoot | `Space` | Fire button (bottom-right) |
| Aim | Auto-locks to nearest zombie | Auto-locks to nearest zombie |

You start with **3 lives**. Survive as long as possible, rack up points, and try to beat your best score — it's saved automatically.

---

## 🗺️ Game Systems Overview

The game is organized into a handful of self-contained systems inside `index.html`:

```
Dead Grid: Infinite Night
├── Input Layer         Keyboard (WASD/Space) + touch joystick & fire button
├── Player System        Movement, aiming, shooting, walk-cycle animation
├── Zombie System         Spawning, pathing toward player, rising difficulty curve
├── Particle System        Muzzle flash, shell casings, blood, gibs, sparks, explosions
├── Ambient/Atmosphere      Drifting dust motes, dynamic light pool, scanlines, vignette
├── Floor & Decals          Checkerboard grid, static cracks/stains, permanent blood decals
└── HUD & Overlays          Score, lives, best score, start screen, game-over screen
```

### 📖 Feature Index

| # | System | What It Does | Status |
|---|---|---|---|
| 1 | [Player Movement](index.html) | WASD/joystick movement with animated walk cycle | ✅ |
| 2 | [Auto-Aim Shooting](index.html) | Locks onto nearest zombie, fires with cooldown | ✅ |
| 3 | [Zombie Spawning](index.html) | Spawns from screen edges, speeds up over time | ✅ |
| 4 | [Particle Effects](index.html) | Muzzle flash, shells, blood, gibs, sparks | ✅ |
| 5 | [Dynamic Lighting](index.html) | Player-following light pool + vignette | ✅ |
| 6 | [Ambient Atmosphere](index.html) | Drifting dust motes + animated scanlines | ✅ |
| 7 | [Persistent Blood Decals](index.html) | Permanent floor stains from zombie kills | ✅ |
| 8 | [High Score Persistence](index.html) | Saved via `localStorage` | ✅ |
| 9 | [Mobile Controls](index.html) | Joystick + fire button, auto-shown on touch | ✅ |

---

## 🛠️ Tech Stack

- **HTML5** + **CSS3** + **Vanilla JavaScript** — no frameworks, no build step
- **Canvas 2D API** for all rendering (grid, characters, particles, lighting)
- **`localStorage`** for high score persistence
- Responsive layout with dedicated mobile touch controls

**Prerequisites:** A modern web browser. That's it.

---

## 🤝 Contributing

Contributions are welcome — new enemy types, weapons, sound, or visual effects!

1. **Fork** this repository
2. **Create** your branch: `git checkout -b feat/your-feature`
3. **Commit**: `git commit -m 'feat: add feature'`
4. **Push**: `git push origin feat/your-feature`
5. **Open a Pull Request**

📋 Read the full [**Contributing Guide →**](CONTRIBUTING.md)

| Type | How |
|---|---|
| 🐛 Found a bug | [Open an Issue](../../issues/new?template=bug_report.md) |
| 💡 Feature idea | [Start a Discussion](../../discussions) |
| 🎨 Visual/gameplay tweak | Submit a Pull Request |

---

## 📄 License

Licensed under the [MIT License](LICENSE) — free to use, modify, and share.

---

**⭐ If you enjoy Dead Grid: Infinite Night, consider starring the repo — it helps others find it!**

Made with 🧟 · Survive the grid, one wave at a time.
