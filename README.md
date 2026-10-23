# AS3 Mario Memory Flip Game
Assignment 3 — Memory matching card game

## Overview
This is a browser-based memory flip card game built with native HTML, CSS and JavaScript.
Players flip cards to find matching icon pairs. The game has a score system and sound feedback for different events.

## How to play
1. Click cards to flip them and reveal icons.
2. Find two identical icons to make a match.
3. Each correct match gains +100 score.
4. Each wrong match deducts 10 score.
5. Match all pairs → Win.
6. Score drops to 0 → Lose.
7. Click "Play Again / Try Again" to restart the game.

## Audio design (key requirement)
- BGM starts playing when you click the first card, and loops.
- `1.mp3`: Correct match sound, BGM continues playing.
- `2.mp3`: Wrong match sound, BGM continues playing.
- `3.mp3`: Win fanfare, BGM stops.
- `4.mp3`: Lose sound, BGM stops.
- After restarting, BGM will trigger again on the first card click.

## Tech stack
- HTML5 for page structure
- CSS for layout, styling, hover and transition animation
- Vanilla JavaScript for game logic, shuffle, flip, scoring and audio control

## Live Demo
https://yanyiming57.github.io/as3/

## Repository
https://github.com/yanyiming57/as3
