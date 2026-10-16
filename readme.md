# NEON XO (Tic-Tac-Toe) - Cyberpunk Edition

A modern, responsive, and neon-styled Tic-Tac-Toe game built with vanilla HTML, CSS, and JavaScript.

![NEON XO](https://img.shields.io/badge/Style-Cyberpunk%20Neon-00f0ff)
![Game-Mode](https://img.shields.io/badge/Modes-2P%20%7C%20AI%20Pro%20%7C%20AI%20Easy-d946ef)
![License](https://img.shields.io/badge/License-MIT-green)

---

## ✨ Features

- **3×3 High-Tech Grid**: Sleek glassmorphism grid with ambient glows.
- **Two-Player Mode (PvP)**: Play locally on the same device with a friend.
- **AI Modes (Pro & Easy)**:
  - **vs AI (Pro)**: Powered by the Minimax decision algorithm with alpha-beta pruning (unbeatable mode).
  - **vs AI (Easy)**: Casual fun play with randomized decisions and defensive blocks.
- **Neon Glow Visuals**:
  - **Player X**: Electric Cyan with radiant drop shadows and text glow.
  - **Player O**: Vibrant Neon Purple/Magenta with smooth glowing pulses.
  - **Winning Highlights**: Animated glowing border and scale animation on the 3 winning cells.
- **Interactive Previews**: Dynamic ghost previews when hovering over empty cells showing the current player's mark.
- **Web Audio Sound Effects**: Zero external audio downloads. Uses the Web Audio API to synthesize futuristic sci-fi blips, victory fanfares, draw chords, and clicks.
- **Confetti & Particle Celebration**: Built-in 60FPS HTML5 canvas particle celebration when a player wins.
- **Persistent Scoreboard**: Saves wins and ties to `localStorage` across page reloads.
- **Keyboard & Accessibility**: Full arrow key navigation (`↑`, `↓`, `←`, `→`), `Space`/`Enter` to place marks, and `Esc` to close modals.
- **Fully Responsive**: Optimized for desktops, tablets, and smartphones.

---

## 🚀 How to Run the Game

### Method 1: Direct File Opening
Double-click [`index.html`](index.html) or right-click and choose **Open with > Chrome / Edge / Firefox / Safari**.

### Method 2: Local HTTP Server (Optional)
If you have Python installed:
```powershell
python -m http.server 3000
```
Then open `http://localhost:3000` in your web browser.

---

## ⌨️ Controls & Shortcuts

| Action | Control |
|---|---|
| Select Cell | Left Click / Tap |
| Grid Navigation | Arrow Keys (`↑`, `↓`, `←`, `→`) |
| Confirm Move | `Enter` or `Space` |
| Close Modal | `Escape` |
| Mute/Unmute Audio | Sound icon in top-right |

---

## 📁 File Structure

```
xo-game/
├── index.html       # Semantic HTML5 layout & modal structure
├── style.css        # Cyberpunk neon styles, glassmorphism & responsive CSS
├── script.js        # Game engine, AI minimax, Web Audio synth, canvas particles
└── README.md        # Documentation
```
