# TicTacToe

A tiny, fast, no-build Tic-Tac-Toe game made with plain HTML, CSS, and JavaScript.

## Why This Project

- Super fast load time
- Zero dependencies
- Single file to understand and edit

## Features

- 3x3 clickable board
- Two-player turn system (X and O)
- Winner detection for all rows, columns, and diagonals
- Draw detection
- One-click reset button
- Mobile-friendly layout

## Quick Start

1. Open [index.html](index.html) in your browser
2. Click any square to place X or O
3. Press Reset to start a new game

## How It Works

- Game state is stored in a 9-cell array
- Turn switches after every valid move
- Win lines are checked after each move
- Game stops when a player wins or when all cells are filled

## Project Structure

- [index.html](index.html): UI, styles, and game logic
- [README.md](README.md): project guide

## Customize Fast

- Change colors in the CSS variables at the top of [index.html](index.html)
- Change board/card sizing in the .app and .cell styles in [index.html](index.html)
- Update text labels in the script section of [index.html](index.html)
