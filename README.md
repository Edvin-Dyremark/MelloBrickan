# MelloBrickan

A bingo card web app for Melodifestivalen and Eurovision. Mark off classic moments as they happen during the show — glitter explosions, key changes, awkward green room interviews, and more.

## Features

- **Two modes** — Melodifestivalen and Eurovision, with mode-specific events filtered accordingly
- **Interactive bingo card** — Click to stamp squares, long-press (mobile) or hover-click the reroll button to swap out individual squares
- **Bingo detection** — Rows, columns, and diagonals are detected with a golden glow effect
- **Confetti celebration** when you hit bingo
- **Print-friendly** — Print your card to bring to a watch party
- **140+ events** covering performances, hosts, audience reactions, voting drama, and general clichés

## Usage

Open `index.html` in a browser. No build step, no dependencies — just a single HTML file and a JS file with the event pool.

- **Nytt kort** — Generate a new randomized card
- **Nollställ** — Clear all stamps without changing the card
- **Skriv ut** — Print the current card

## Project Structure

```
index.html    — App UI, styling, and game logic
events.js     — Pool of bingo events with optional mode exclusions
favicon.svg   — Site icon
```
