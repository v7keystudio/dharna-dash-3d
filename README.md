<div align="center">

# 🏃 DHARNA DASH 3D

### Run the streets. Dodge the chaos. Own the leaderboard.

**A fictional, comedy-driven 3D endless runner set in a Delhi-inspired world.**

[![Live Demo](https://img.shields.io/badge/PLAY_NOW-LIVE_DEMO-FF914B?style=for-the-badge&logo=vercel&logoColor=white)](https://v7keystudio.vercel.app)
[![Three.js](https://img.shields.io/badge/Three.js-0.160.0-black?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Made by V7KEYSTUDIO](https://img.shields.io/badge/CREATED_BY-V7KEYSTUDIO-7D3425?style=for-the-badge)](https://github.com/v7keystudio)

**[🎮 Play Live](https://v7keystudio.vercel.app)** · **[👨‍💻 Developer](https://github.com/v7keystudio)**

</div>

---

## ✨ Overview

**Dharna Dash 3D** is a lightweight, browser-based endless runner built with **Three.js, HTML5, CSS3, and vanilla JavaScript**. Sprint through three lanes, avoid barricades and traffic, collect tokens, unlock fictional characters, and outrun security in a stylized Delhi-inspired environment.

The game uses **procedurally assembled 3D objects** rather than downloaded character or scenery models. Its interface mixes warm sunset colors, responsive HUD elements, and Hinglish comedy dialogue.

> **Disclaimer:** All playable characters are fictional. This project is a comedy game and is not affiliated with any political figure, organization, or institution.

## 🚀 Features

- **3D endless runner:** Three-lane gameplay with progressively increasing speed.
- **Responsive controls:** Keyboard, mobile swipe gestures, and on-screen touch buttons.
- **Four playable characters:** Distinct speed, jump, and power attributes; two unlockable with in-game tokens.
- **Dynamic obstacles:** Barricades, crowds, banners, tea stalls, and cars.
- **Collectibles and power-ups:** Coins, chai speed boost, shield, and coin magnet.
- **Boss moments:** Special obstacle patterns with one safe lane.
- **Persistent progress:** Best score, token balance, and character unlocks saved using `localStorage`.
- **Game interface:** Live score, distance, speed, coin count, security proximity, pause/restart, sound toggle, and fullscreen.
- **Code-generated assets:** Environment and character geometry created with Three.js primitives.

## 🎮 Controls

| Action | Desktop | Mobile |
| :-- | :-- | :-- |
| Move left | `←` or `A` | Swipe left / `←` button |
| Move right | `→` or `D` | Swipe right / `→` button |
| Jump | `↑`, `W`, or `Space` | Swipe up / `↑` button |
| Slide | `↓` or `S` | Swipe down / `↓` button |
| Pause | `Esc` | Pause button |

**Objective:** Keep running, collect tokens, and avoid two collisions. Some obstacles can be jumped over, while low banners require sliding.

## 🧑‍🚀 Characters

| Character | Specialty | Unlock cost |
| :-- | :-- | --: |
| Neta Dhamaka Ji | Faster running | Free |
| Bhaiya Cycle Singh | Balanced performance | Free |
| Didi Jhaadu Devi | Higher jumps | 120 tokens |
| Baba Bulldozer | Breaks barricades | 180 tokens |

## 🛠️ Tech Stack

| Technology | Purpose |
| :-- | :-- |
| HTML5 | Application structure and game canvas |
| CSS3 | Responsive UI, overlays, and HUD |
| JavaScript (ES6+) | Game loop, input, collisions, scoring, and progression |
| Three.js `0.160.0` | 3D scene, models, camera, lighting, and rendering |
| WebGL | Hardware-accelerated graphics |
| Web Audio API | Generated game sound effects |
| Local Storage | Browser-local game progress |

## 💻 Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/v7keystudio/dharna-dash-3d.git
   cd dharna-dash-3d
   ```

2. Start a local web server:

   ```bash
   python -m http.server 8000
   ```

3. Open **http://localhost:8000** in a WebGL-capable browser.

> **Internet required:** The game loads Three.js from cdnjs and the Inter font from Google Fonts. The project has no build step or npm dependencies.

## 📁 Project Structure

```text
dharna-dash-3d/
├── index.html    # Game, styles, and JavaScript
└── README.md     # Project documentation
```

## 🌐 Deployment

The project is a static website and can be deployed to **Vercel**, GitHub Pages, Netlify, or any static web host.

For Vercel, import the GitHub repository, select **Other** as the framework preset if prompted, and deploy with no build command. Keep `index.html` in the repository root.

**Live URL provided by the developer:** https://v7keystudio.vercel.app

## 🧭 Potential Improvements

- Add a screenshot gallery and short gameplay preview.
- Add accessibility settings and adjustable graphics quality.
- Optimize geometry and rendering for low-end devices.
- Add automated gameplay tests and a versioned release process.
- Introduce an optional online leaderboard with appropriate backend validation.

## 👨‍💻 Developer

Created by **[V7KEYSTUDIO](https://github.com/v7keystudio)**.

Explore the project, try the live game, and share feedback through GitHub issues once the repository is published.

---

<div align="center">

**Built with JavaScript, Three.js, and a little chaos. ⚡**

[Live Game](https://v7keystudio.vercel.app) · [GitHub Profile](https://github.com/v7keystudio)

</div>
