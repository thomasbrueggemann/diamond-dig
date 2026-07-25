# 💎 Diamond Dig

A fast-paced digging game built with Three.js. Hunt for hidden diamonds on a grid — but watch the clock!

## How to Play

- **Click/tap anywhere** on the ground to dig — your dig will snap to the nearest grid cell
- Find **8 hidden diamonds** hidden across a 10×10 grid
- You get **30 digs** and **90 seconds** — use them wisely
- Hover (desktop) or touch (mobile) to see proximity clues:
  - 🔥 Very Close!
  - 👍 Close
  - 👌 Somewhat Near
  - 🤷 Getting Far
  - ❄️ Very Far
- Use the **🔮 Hint** button (costs 50 points) to get a directional clue to the nearest diamond

## Scoring

- **+100 points** for each diamond found
- **-10 points** for each miss
- **-50 points** for using a hint

## Game Over

The game ends when you:
- Find all 8 diamonds (you win!)
- Run out of digs
- Time runs out

## Built With

This game was built entirely with local AI — **Qwen 3.6 35B A3B** running locally. No external AI services were used.

## Tech Stack

- **Three.js** — 3D rendering
- **Single HTML file** — no build tools, no dependencies to install
- **Touch + mouse support** — works on desktop and mobile

## Play Online

[🎮 Play the game](https://thomasbrueggemann.github.io/diamond-dig/)

## Local Development

Just open `index.html` in any modern browser. No server required.
