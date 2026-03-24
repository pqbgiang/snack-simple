# 🐍 Snake Game

A classic Snake game running locally in your browser, served by Express.

## Quick Start

```bash
npm install
npm start
```

Then open **http://localhost:3000**

## Controls

| Key | Action |
|-----|--------|
| `↑ ↓ ← →` or `W A S D` | Move |
| `P` | Pause / Resume |

## Gameplay

- Eat the **red dot** to grow and score points
- Every 5 points → level up (speed increases)
- Every 10 points → a **golden diamond** bonus spawns (worth 3 pts, disappears after 5s)
- High score is saved in `localStorage`

## Dev mode (auto-restart on file change)

Requires Node.js 18+:

```bash
npm run dev
```

## Project Structure

```
snake-game/
├── server.js        # Express static server
├── package.json
└── public/
    └── index.html   # Game (HTML + CSS + JS, self-contained)
```
