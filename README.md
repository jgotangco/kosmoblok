# 🚀 KOSMOBLOK

> *Sovetskiy Famicom Edition — 1984*

A Soviet space-themed, Famicom-style block-stacking game built as a single self-contained HTML file. No dependencies, no build step — just open and play.

![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)
![Made with HTML5 Canvas](https://img.shields.io/badge/Made%20with-HTML5%20Canvas-cc0000)

---

## 🎮 Features

- **Classic block-stacking gameplay** — 7 tetrominoes with wall-kick rotation
- **Famicom-style pixel art** — 3-shade block rendering with highlight, body, and shadow
- **Ghost piece** — shows where the block will land
- **Soviet space background** — animated Kremlin silhouette, flying rockets, Sputnik satellites, hammer & sickle symbols, Soviet red stars, and orbit trails
- **Animated Matryoshka doll** — blinking eyes that look left, right, up, and down with smooth interpolation
- **Chiptune music** — Korobeiniki (Tetris Theme A) generated via Web Audio API using square wave + triangle bass + noise percussion
- **Sound effects** — land, rotate, line clear, Tetris (4-line), and game over
- **10 speed levels** — increases every 10 lines cleared
- **CRT scanline overlay** — authentic retro feel

---

## 🕹️ Controls

| Key | Action |
|---|---|
| `← →` Arrow Keys | Move piece left / right |
| `↑` Arrow Key | Rotate piece |
| `↓` Arrow Key | Soft drop |
| `Space` | Hard drop (instant) |
| `P` | Pause / Resume |
| `M` | Toggle music |
| `Enter` | Start / Restart game |

---

## 🚀 How to Play

1. Download or clone this repository
2. Open `kosmoblok.html` in any modern web browser
3. Press **Enter** to start
4. Stack blocks, clear lines, and survive as long as you can!

**Scoring:**
| Lines Cleared | Points (× Level) |
|---|---|
| 1 line | 100 |
| 2 lines | 300 |
| 3 lines | 500 |
| 4 lines (KOSMOBLOK!) | 800 |

Hard drops award **+2 points per row** dropped.

---

## 🛠️ Technical Details

- Pure **HTML5 + Canvas 2D + Web Audio API** — zero dependencies
- Single self-contained `.html` file (~30KB)
- All graphics drawn procedurally with canvas primitives
- Music scheduled ahead-of-time using the Web Audio API for gapless looping
- Matryoshka doll eye animation uses a state machine with smooth lerp interpolation

---

## 📄 License

MIT License

Copyright (c) 2026 Jerome Gotangco

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

*Designed and product-directed by [Jerome Gotangco](https://github.com/jgotangco). Developed with [Google Antigravity](https://antigravity.dev) / Gemini.*

★ SSSR ★ MOSKVA ★ 1984 ★