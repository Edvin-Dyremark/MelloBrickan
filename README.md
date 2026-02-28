# MelloBrickan

A bingo card web app for Melodifestivalen and Eurovision. Mark off classic moments as they happen during the show: glitter explosions, key changes, awkward green room interviews, and more. Perfect for making the "MelloKväll" at home or with friends even more interesting.

## Features

- **Two modes**: Melodifestivalen and Eurovision, with mode-specific events filtered accordingly
- **Interactive bingo card**: Click to stamp squares, long-press (mobile) or hover-click the reroll button to swap out individual squares
- **Generate Cards**: Generate bingo cards, re-roll individual boxes, and more.
- **Print-friendly**: Recommended: Print your card to bring to a watch party, or host your own!
- **140+ events** covering performances, hosts, audience reactions, voting drama, and general clichés

## Usage

Open `index.html` in a browser. No build step, no dependencies — just a single HTML file and a JS file with the event pool.

- **Nytt kort**: Generate a new randomized card
- **Nollställ**: Clear all stamps without changing the card
- **Skriv ut**: Print the current card

## Project Structure

```
index.html    — App UI, styling, and game logic
events.js     — Pool of bingo events with optional mode exclusions
favicon.svg   — Site icon
```
