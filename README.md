# SK Games

A collection of classic browser games by [Shalom Karr](https://shalomkarr.pages.dev/).

Pure HTML/JS — no installs, no accounts, no ads. Companion to [SK Tools](https://sk-tools.pages.dev/).

## Games

| Game | Page | What's good about it |
|---|---|---|
| ♚ Chess | [`/chess.html`](chess.html) | PvP or vs CPU, legal-move highlights, undo, save mid-game |
| ⛀ Checkers | [`/checkers.html`](checkers.html) | Forced captures, king promotion, multi-jump chains |
| 🔴 Connect Four | [`/connect-four.html`](connect-four.html) | Smooth gravity drop, win highlighting, vs CPU |
| ⭕ Tic-Tac-Toe | [`/tictactoe.html`](tictactoe.html) | Unbeatable minimax bot — you can't win, only draw |
| 🐺 Wolf & Sheep | [`/wolf-sheep.html`](wolf-sheep.html) | Asymmetric chase game on an 8×8 board |
| 🃏 Memory Match | [`/memory.html`](memory.html) | Three difficulties, move counter, best-time leaderboard |

## Design principles

1. **No build step.** Tailwind CDN + vanilla JS. Open `index.html` in a browser, it works.
2. **One design language.** All games share `assets/skgames.css` and a sticky nav.
3. **Phone-friendly.** Every game is touch-playable and works in portrait.
4. **Save state.** Best times and unfinished games persist in `localStorage`.

## Stack

- **Tailwind CSS** (CDN)
- **Vanilla JS** — no framework
- **Inter** font from Google Fonts
- Shared brand: violet (vs SK Tools' blue), so the suite is visually grouped but distinct.

## Local dev

```bash
npx serve .
# or
python -m http.server 8000
```

## Deployment

Static site — drop on Cloudflare Pages, Netlify, GitHub Pages, or any static host.

---

Open a tab, play a round.
