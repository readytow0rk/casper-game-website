# Pick Up Casper 👻

<div align="center">

**A fast-paced reaction-testing browser game — how quick are your reflexes?**

[![Live Demo](https://img.shields.io/badge/▶%20Play%20Now-Live%20Demo-brightgreen?style=for-the-badge)](https://readytow0rk.github.io/casper-game-website/)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://readytow0rk.github.io/casper-game-website/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap%205.2-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

</div>

---

## 🌐 Live Version

> **[https://readytow0rk.github.io/casper-game-website/](https://readytow0rk.github.io/casper-game-website/)**

Play directly in your browser — no installation, no downloads.

---

## About

Pick Up Casper is a whack-a-mole style reaction game. A ghost named Casper randomly appears across a 3×3 grid, and your goal is simple: **tap or click the ghost as many times as possible within 15 seconds**. Five difficulty levels let anyone play — from young kids to competitive speedrunners.

Challenge your friends to beat your score!

---

## Features

### 🎮 Gameplay
- **3×3 interactive grid** where ghosts randomly appear and disappear
- **15-second rounds** — fast, replayable, and competitive
- **Live score counter** updates with every successful hit
- **Countdown timer** displayed throughout the round

### ⚙️ Settings & Customization
| Feature | Description |
|---|---|
| **5 Difficulty Levels** | From 700ms (kids) to 100ms (extreme) spawn intervals |
| **7 Color Themes** | Cycle through glow colors: red, yellow, cyan, magenta, pink, white |
| **Fullscreen Mode** | Immersive full-screen gameplay toggle |
| **Refresh Button** | Safely resets game state when switching difficulty mid-round |

### 📱 Responsive Design
Tested and working across a wide range of devices:
- iPhone SE, Pixel 5, Samsung Galaxy S8+, Galaxy S Ultra
- iPad Air, iPad Mini, Surface Pro 7
- Desktop and laptop resolutions

---

## Difficulty Levels

| Level | Spawn Speed | Intended For |
|---|---|---|
| 1 | 700ms | Kids / Beginners |
| 2 | 600ms | Casual players |
| 3 | 400ms | Regular players |
| 4 | 250ms | Experienced players |
| 5 | 100ms | Reaction masters |

---

## How to Play

1. Open the [live site](https://readytow0rk.github.io/casper-game-website/)
2. Click **Settings** to choose your difficulty and customize the color theme
3. Click **Start** to begin the round
4. **Tap/click Casper** every time the ghost appears on the grid
5. Your score is shown at the end of the 15-second round
6. Challenge a friend to beat it!

> **Tip:** If you switch difficulty before a round ends, press the **Refresh** button first to avoid timer conflicts.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and game grid |
| CSS3 | Glow effects, color themes, responsive layout |
| Vanilla JavaScript | All game logic, DOM manipulation, timers |
| Bootstrap 5.2 | UI components and responsive grid system |
| GitHub Pages | Free static hosting and deployment |

---

## Project Structure

```
casper-game-website/
├── index.html          # Main HTML file — full game UI
├── cover/
│   ├── main.js         # Core game logic (46 functions, 593 lines)
│   ├── cover.css       # Game-specific styles and color themes
│   └── casper1.png     # Ghost sprite image
├── assets/
│   └── dist/
│       ├── css/        # Bootstrap 5.2 CSS bundles
│       └── js/         # Bootstrap 5.2 JS bundles
└── media/              # Documentation assets
```

---

## Deployment

The site is deployed via **GitHub Pages**:

1. Navigate to the repository **Settings** tab
2. Under **Pages**, set the source to the `master` branch
3. GitHub Pages automatically builds and serves the site

Live at: [https://readytow0rk.github.io/casper-game-website/](https://readytow0rk.github.io/casper-game-website/)

---

## Known Issues

- **Mid-round difficulty switch:** Switching levels before a round ends without pressing Refresh causes two timers to run simultaneously, resulting in conflicting score and time displays. **Fix: always press Refresh when changing difficulty mid-game.**

---

## Credits

- Ghost image sourced from [Unsplash](https://unsplash.com/)
- Bootstrap 5.2 starter template by [@mdo](https://twitter.com/mdo)

---

## Author

**Nikita** — sole developer and designer of this project.

[![GitHub](https://img.shields.io/badge/GitHub-readytow0rk-181717?style=flat-square&logo=github)](https://github.com/readytow0rk)
