# Морской сапёр 🫧

A small sea-themed Minesweeper in a single HTML file, built with React.

## How to play

Open `game.html` in any browser. No install or build step is needed. It does need an internet connection, because React and Babel load from a CDN.

- **Click / tap** to open a cell
- **Right-click / long-press (0.7 s)** to place a flag
- Board: 9 × 9 with 10 mines. Your first move is always safe, because the 3 × 3 area around it never has a mine.
- Pick your flag before the game starts: ⭐ 🪸 🐟 🐚

## Features

- Timer and mine counter
- Mobile-friendly touch controls
- The board is checked after it is generated. Set `DEBUG_BREAK = true` in the code to see the check catch a broken board.
