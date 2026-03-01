# 2D Runner — Playable Ad

A casual 2D side-scrolling runner built with vanilla JavaScript and HTML5 Canvas. Fully self-contained single-file bundle — no dependencies, no build tools required.

## Play

Open `index.html` in any modern browser, or deploy to any static hosting (Vercel, Netlify, GitHub Pages).

---

## Backlog

### ✅ Done

| # | Feature |
|---|---------|
| 1 | Core runner loop — player, enemies, coins, lives |
| 2 | SpacedSpriteSheet & EvenGridSpriteSheet renderers |
| 3 | Parallax background with two-pass lamp layering |
| 4 | Cooper Black / Lilita One font stack |
| 5 | EVADE! badge on cone enemies |
| 6 | Red 3D CTA button (INSTALL AND EARN) |
| 7 | PayPal card reward screen |
| 8 | Tutorial system — enemy runs toward player, scene freezes, jump unlocks on proximity |
| 9 | Jump-blocked before tutorial trigger |
| 10 | Screen shake on hit |
| 11 | Squash & stretch on land |
| 12 | Blink animation via spritesheet frames |
| 13 | Confetti FX on score milestone & win/lose |
| 14 | Finish line with checkerboard tape on win |
| 15 | Collectible PayPal card coin variant |
| 16 | Decoration spacing algorithm (per-group minSpacing) |
| 17 | Lamp posts rendered in front of trees and bushes |
| 18 | Fixed animation jerking (uniform source rect for all frames) |
| 19 | Background flicker fix — sky fill + extra tile + Math.round |
| 20 | Start screen — no overlay, no underlay, text shadow only |
| 21 | Casual difficulty tuning — slower enemies, longer spawn intervals |
| 22 | Smaller player hitbox (torso only) |
| 23 | Single-file bundle with all assets as base64 data URIs (3.87 MB) |

---

### 🔲 Planned

| Priority | Feature |
|----------|---------|
| High | Sound effects — jump, coin collect, hit, win |
| High | Mobile haptic feedback on jump & hit |
| Medium | Coin magnet power-up |
| Medium | Shield power-up (one free hit) |
| Medium | Animated background elements (birds, clouds) |
| Medium | Leaderboard / score persistence (localStorage) |
| Low | Second enemy type — rolling barrel |
| Low | Day → night cycle background transition |
| Low | Accessibility — reduced-motion mode |
| Low | Localization (EN / UA / RU) |

---

## Tech

- **Renderer:** HTML5 Canvas 2D
- **Assets:** PNG / WebP, embedded as base64
- **Bundle size:** 3.87 MB (under 5 MB ad limit)
- **No framework, no bundler** — pure vanilla JS
