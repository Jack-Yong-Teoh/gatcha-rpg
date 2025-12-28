# ✦ Astral Gacha: Elemental Legends

[![Live Demo](https://img.shields.io/badge/demo-online-blue.svg)](https://jack-yong-teoh.github.io/astral-gacha/)
[![Vue.js](https://img.shields.io/badge/Framework-Vue%203-42b883.svg)](https://vuejs.org/)
[![TailwindCSS](https://img.shields.io/badge/Style-Tailwind-06b6d4.svg)](https://tailwindcss.com/)

An immersive, high-fidelity browser-based Gacha RPG built with **Vue 3** and **Tailwind CSS**. Experience a modular combat system, real-time elemental VFX, and a deep character progression engine.

**[🎮 Play the Live Demo Here](https://jack-yong-teoh.github.io/astral-gacha/)**

---

## ✨ Core Systems

### ⚔️ Elemental Combat Engine
* **Real-time Battle Loop:** Integrated `requestAnimationFrame` engine managing Boss AI and Squad cooldowns.
* **VFX Layering:** Custom CSS-driven elemental effects (Thunder, Sakura, Inferno, Life) that trigger based on character attributes.
* **Dynamic Damage Feedback:** Real-time physics-based damage numbers and screen-shake feedback.

### 💎 Advanced Gacha Mechanics
* **Pity System:** Accurate "Soft Pity" (starting at 53 pulls) and "Hard Pity" (guaranteed 5★ at 70 pulls) logic.
* **50/50 Mechanics:** Event-specific banners with "Guarantee" flags stored in persistent state.
* **Summoning Rituals:** Cinematic pull sequences using high-quality assets and synchronized audio.

### 📜 Progression & Barracks
* **Unit Leveling:** XP-based ascension system requiring duplicate character shards.
* **Stats Scaling:** Logarithmic power scaling (CP) based on rarity and level.
* **Persistence:** Full game state (Gems, Inventory, Pity, Map Progress) saved via `localStorage`.

---

## 🛠️ Tech Stack

* **Logic:** Vue 3 (Composition API)
* **Styling:** Tailwind CSS (JIT Engine)
* **Database:** Modular JS-based Entity System
* **Audio:** Web Audio API & Audio Object Management
* **Animations:** CSS3 Keyframes & Vue Transition Groups

---

## 🚀 Local Setup

Because the project uses **ES6 Modules**, you must run it through a local web server to avoid CORS policy restrictions.

### 1. Clone the repository
```bash
git clone https://github.com/Jack-Yong-Teoh/gatcha-rpg.git
cd astral-gacha
