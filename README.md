# 🌌 Stellar Merge

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0-5ef2ff?style=for-the-badge&logo=semver&logoColor=black" alt="Version 1.0">
  <img src="https://img.shields.io/badge/platform-Web%20%7C%20Mobile-ff5ee0?style=for-the-badge" alt="Platform Web / Mobile">
  <img src="https://img.shields.io/badge/license-GPL--3.0-ffd66b?style=for-the-badge&logoColor=black" alt="License GPL 3.0">
  <img src="https://img.shields.io/badge/dependencies-0%20(Pure%20Vanilla)-brightgreen?style=for-the-badge" alt="Zero Dependencies">
</p>

<p align="center">
  A polished, zero-dependency cosmic physics puzzler built for the modern browser.<br>
  Drop matter into the gravity well, fuse identical worlds, trigger cascading combos, and forge a supermassive Black Hole without overflowing the Event Horizon.
</p>

<p align="center">
  👉 <b><a href="https://thee1even11.github.io/Stellar-Merge/">Play Stellar Merge Online</a></b> 👈
</p>

---

## ✨ Features

- **Juicy & Responsive Core Loop:** Dynamic screen shake, radial shockwaves, particle bursts, squash-and-stretch impacts, and harmonic pitched sound effects.
- **Custom Verlet Physics Engine:** 8 sub-steps per frame, mass-weighted separation, smooth growth upon fusion, tangential friction, and restitution bouncing.
- **Synthesized Audio (Web Audio API):** 100% procedural sound effects—no audio files, assets, or network latency.
- **Cross-Platform Controls:** Smooth touch-and-drag controls for mobile alongside responsive keyboard and mouse controls for desktop.
- **Local Leaderboard:** Saves your top 8 personal records, highest celestial tier unlocked, and timestamps via `localStorage`.
- **Zero Build Step:** 100% self-contained in a single, lightweight `index.html`. Fully compatible with GitHub Pages out of the box.

---

## 🎮 How to Play

1. **Aim** matter along the top axis.
2. **Drop** it into the gravity well.
3. When two bodies of the **same tier collide**, they fuse into the next tier.
4. **Combo Multipliers:** Trigger consecutive merges within 1.4 seconds to rack up exponential bonus points.
5. **Singularity:** Merge two Black Holes to trigger total annihilation for a massive score reward!
6. **Watch the Line:** Do not let settled matter rest above the **Event Horizon** for more than 1.6 seconds, or the well collapses.

---

## 🪐 The Fusion Chain

| Tier | Celestial Body | Radius | Base Value |
| :---: | :--- | :---: | :---: |
| **0** | ⚪ Dust | 13 px | 10 pts |
| **1** | 🪨 Pebble | 19 px | 30 pts |
| **2** | 🌑 Asteroid | 26 px | 60 pts |
| **3** | ☄️ Comet | 34 px | 100 pts |
| **4** | 🌕 Moon | 43 px | 150 pts |
| **5** | 🌍 Terrestrial Planet | 53 px | 210 pts |
| **6** | 🪐 Gas Giant | 64 px | 280 pts |
| **7** | ☀️ Star | 76 px | 360 pts |
| **8** | 🔴 Red Giant | 90 px | 450 pts |
| **9** | 💠 Neutron Star | 105 px | 550 pts |
| **10** | 🕳️ Black Hole | 121 px | 660 pts *(1,000+ on Annihilation)* |

---

## 🕹️ Controls

| Action | Desktop (Keyboard / Mouse) | Mobile (Touch) |
| :--- | :--- | :--- |
| **Aim** | `←` / `→` or `A` / `D` or Mouse Move | Touch & Drag |
| **Drop** | `Space` / `↓` / `Enter` / Left Click | Release Finger |
| **Pause / Resume** | `P` / `Escape` or Click `❚❚` | Tap `❚❚` |
| **Quick Restart** | `R` (or during Game Over) | "Play Again" button |
| **Mute / Unmute** | `M` | Tap `🔊` icon |

---

## 🔢 Versioning Scheme

This project follows a streamlined two-tier versioning pattern:
* **Feature / Major Release:** `X.Y` *(e.g., 1.0, 1.1, 1.2)*
* **Hotfix / Patch Release:** `X.Y1` *(e.g., 1.01, 1.11, 1.21)*

---

## 📜 Changelog

### `1.0` *(Initial Release)*
- Complete 11-tier cosmic fusion puzzle mechanic with score and combo systems.
- Stabilized custom Verlet physics solver running at 60 FPS with gradual body scaling on merge and velocity caps.
- Procedural audio synthesizer using the Web Audio API.
- Unified touch, mouse, and keyboard input handling.
- Event Horizon overflow detection with settled-body velocity thresholding.
- Local high-score table and responsive HUD.

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for details.
