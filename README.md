# 🎰 KTO Fortune — Slot Game

A free-to-play 3-reel slot game built with vanilla HTML, CSS, and JavaScript. No dependencies, no build step — just open `index.html` in a browser or deploy to any static host.

## Features

- **3 reels × 3 rows** classic slot layout
- **5 paylines** — middle, top, bottom, and both diagonals
- **10 symbols** including WILD (substitutes for any symbol)
- **2× and 3× match payouts** — two-of-a-kind pays too
- Staggered reel spin animations
- Gold glow win highlights + confetti particles on Big Wins
- Auto-spin mode
- Adjustable bet levels (R$0.50 → R$50.00)
- Collapsible paytable
- Dark theme with KTO red (#DA0000) accents

## Project Structure

```
kto-fortune-slot/
├── index.html          # Main game (self-contained)
├── assets/
│   ├── KTO-fortune.png # Game logo
│   └── symbols/        # All 10 reel symbols
│       ├── coin.png
│       ├── mate.png
│       ├── tiger.png
│       ├── gold.png
│       ├── cracker.png
│       ├── caipirinha.png
│       ├── wild.png
│       ├── K.png
│       ├── T.png
│       └── O.png
└── README.md
```

## Getting Started

### Local
Just open `index.html` in any modern browser — no server required.

### GitHub Pages
1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your game will be live at `https://<username>.github.io/<repo>/`

## Symbol Payouts

| Symbol      | 2× match | 3× match |
|-------------|----------|----------|
| WILD        | 5×       | 50×      |
| KTO Coin    | 3×       | 20×      |
| KTO Mate    | 2×       | 15×      |
| Tiger       | 2×       | 10×      |
| Gold Bar    | 1×       | 8×       |
| Cracker     | 1×       | 6×       |
| Caipirinha  | 1×       | 5×       |
| K           | —        | 3×       |
| T           | —        | 3×       |
| O           | —        | 2×       |

> WILD substitutes for any symbol and completes winning combinations.

## Tech Stack

- Vanilla HTML5 / CSS3 / JavaScript (ES2020)
- Google Fonts — Inter
- Canvas API for win particle effects
- No frameworks, no build tools
