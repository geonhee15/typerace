# typerace

A fast-paced web typing game. How far can you go before the clock runs out?

Play in the browser — no install, no build. Just open `index.html`.

## Features

- **Three difficulties** — easy (30s), normal (25s), hard (20s)
- **420 English sentences** across the three pools
- **Per-sentence timer** — the countdown resets every time you clear a sentence, so keep the streak alive
- **Live stats** — level, WPM and accuracy update in real time, top right
- **Character-by-character feedback** — correct letters turn white, mistakes flash red
- **Best records** — your top level per difficulty is saved locally (localStorage) and shown on the menu

## How to play

1. Open `index.html` in any modern browser.
2. Pick a difficulty and hit **START**.
3. Type the sentence shown. Clear it before the timer hits zero to advance a level and reset the clock.
4. Press **Esc** any time to end the run and see your results.

## Tech

Single static HTML file — vanilla HTML, CSS and JavaScript. No dependencies.
