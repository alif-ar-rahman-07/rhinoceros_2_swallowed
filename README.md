# 🦏 Rhinoceros Emperor Game - Slitherlink Edition

An interactive, high-tech logic puzzle game inspired by the legendary **Rhinoceros Emperor Bureau (犀皇局)** trial from the Chinese web novel and donghua animation series ***Swallowed Star (吞噬星空)***. 

This game brings the core rules of the God King's legacy inheritance trial to life using **Slitherlink (Loopy)** mechanics. Players must use logic and willpower to construct a single, unbroken spatial loop matrix based on structural numeric hints without leaking energy into open dead-ends.

---

## 🎮 Game Concepts & Rules

1. **The Grid Matrix:** The board consists of an arena of intersection nodes (vertices) and empty space boundaries.
2. **Structural Array Coordinates (Hints):** The numbers inside the square quadrants (`0`, `1`, `2`, `3`) indicate exactly **how many border lines must surround that specific box**.
   - A box marked `3` must be bordered by exactly 3 active energy lines.
   - A box marked `0` must remain completely clear of any touching lines.
3. **The Inheritance Target:** Click the empty pathways between the dots to turn lines on and off. You must connect all active lines to form a **single, continuous closed loop** that perfectly weaves across the entire arena without intersecting itself, splitting, or branching off.

---

## 🔥 Key Features

- **12 Progressive Campaign Levels:** Master the foundational array layers! Start on a quick 2x2 grid in the early bureaus to learn the laws of the universe, and watch the matrix expand dynamically up to a grand 4x4 arena by Level 12.
- **Adjustable Modes:** Switch instantly between the standard **Puzzle Mode** single-player campaign and the competitive **Rhino Duel** grid rules layout.
- **Interactive Metrics Console:** A sleek, cyberpunk terminal dashboard that tracks your real-time **Completion Percentage** and **Comprehension Status**.
- **Pure Lightweight Source:** Built using clean, responsive HTML5, CSS3 Grid layouts, and Vanilla JavaScript. Runs 100% offline without needing complex downloads or heavy installation processes.

---

## 📂 Project Structure

To maintain a clean configuration architecture, separate the source code into the following standard web modules:

```text
├── index.html        # App UI Structure & Core Framework
├── style.css         # Cyberpunk Terminal Themes & Starfield Space Graphics
├── script.js         # Computational Logic, Level Matrices & Victory Validations
└── README.md         # Documentation & Deployment Instructions
```

---

## ⚡ Setup & Play Instructions

You don't need any special developer software, servers, or compilation tools to play this game. Follow these simple steps:

### Running Locally on Your PC
1. Download or clone this repository to a folder on your computer.
2. Ensure `index.html`, `style.css`, and `script.js` are all saved together inside that **same single folder**.
3. **Double-click `index.html`** to launch your puzzle arena instantly in any modern web browser (Google Chrome, Microsoft Edge, Safari, Firefox).

### Playing with Friends (Multiplayer Duel / Sharing)
* **Progressive Web App Method:** Open the chat link on your smartphone's browser, tap the browser's menu option (the three dots on Android or the Share icon on iOS), and select **"Add to Home Screen"**. The game will launch in a fullscreen app window completely offline. Pass the device back and forth to race each other's solve times!
* **CodePen Deployment:** If you want a quick link to send friends online, copy the components into a new pen on [CodePen.io](https://codepen.io) (HTML to HTML, CSS to CSS, JS to JS). CodePen will instantly generate a live shareable URL your friends can play on.

---

## 🏆 The 12 Bureaus of Cultivation

The game scales dynamically across three major cultivation tiers:

* **Bureaus 1 to 4:** *Trainee Phase* (2x2 Matrix) — Learn the base micro-geometries.
* **Bureaus 5 to 8:** *Cosmic Breakthrough* (3x3 Matrix) — Manage complex line balances under pressure.
* **Bureaus 9 to 12:** *God King Inheritance* (4x4 Matrix) — The ultimate test of willpower and spatial calculation logic.

*Good luck on your breakthrough journey, Cultivator! May your mind grasp the underlying laws of the universe.*
