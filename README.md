# 2048 Game

A polished, single-file implementation of the classic **2048** sliding-tile puzzle, with a twist: cleared boards roll into progressively harder levels.

Slide numbered tiles on a 4×4 grid; when two tiles with the same number touch, they merge into one whose value is their sum. Reach the level's goal tile to advance to the next level — the board carries over, so your progress isn't reset.

## Features

- **Level progression** — hit the target tile (2048 → 4096 → 8192 → … → 65536) to clear a level and take on a bigger goal. Clear them all to become Champion.
- **Score & best tracking** — your best score is saved between sessions via `localStorage`.
- **Keyboard controls** — arrow keys to slide tiles.
- **Touch controls** — swipe on mobile to move.
- **Smooth animations** — tiles spawn and merge with subtle transitions.
- **Responsive layout** — adapts from wide desktop down to small phones.

## How to play

1. Open `index.html` in any modern browser — no build step or server required.
2. Use the **arrow keys** (or **swipe** on touch devices) to slide all tiles in one direction.
3. Merge matching tiles to build toward the goal shown in the **Level** panel.
4. Reach the goal to clear the level and press **Next Level →**, or keep playing.
5. Press **New Game** at any time to start over from level 1.

The game ends when the board is full and no more moves are possible.

## Tech

- Vanilla HTML, CSS, and JavaScript — everything lives in `index.html`.
- No dependencies, no backend; runs entirely client-side.

## Files

- `index.html` — the complete game (markup, styles, and game logic).
- `manifest.json` — project metadata.
