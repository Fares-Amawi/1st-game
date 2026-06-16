# MENA Space Defender

A browser-based arcade space shooter inspired by classic Space Invaders gameplay.

## Overview

MENA Space Defender is a fast-paced HTML5 Canvas game where players defend the region from waves of alien invaders. The game features responsive controls, animated particle effects, progressive difficulty, wave-based enemy spawning, and support for both desktop and mobile devices.

## Features

- HTML5 Canvas rendering
- Responsive fullscreen gameplay
- Multiple enemy types:
  - Basic enemies
  - Mid-tier enemies
  - Elite enemies
- Wave progression system
- Score tracking
- Lives system
- Particle explosion effects
- Animated starfield background
- Keyboard controls
- Mobile touch controls
- Game over and restart functionality

## Controls

### Desktop

| Key | Action |
|------|---------|
| ← / A | Move Left |
| → / D | Move Right |
| Space | Shoot |

### Mobile

| Screen Area | Action |
|-------------|---------|
| Left Side | Move Left |
| Right Side | Move Right |
| Center | Shoot |

## Game Mechanics

### Scoring

| Enemy Type | Points |
|------------|---------|
| Basic | 10 |
| Mid | 20 |
| Elite | 30 |

### Waves

- Each cleared wave increases difficulty.
- More enemies spawn as waves progress.
- Enemy movement speed increases over time.
- Enemy firing frequency becomes higher.

### Lives

Players start with **3 lives**.

A life is lost when:
- An enemy projectile hits the player.

The game ends when:
- All lives are lost.
- Enemies reach the bottom of the screen.

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- HTML5 Canvas API

## Project Structure

```
index.html
├── UI Layer
├── Canvas Rendering
├── Game Logic
├── Enemy System
├── Particle Effects
├── Input Handling
└── Wave Management
```

## Running the Game

1. Download the project files.
2. Open `index.html` in any modern web browser.
3. Click **LAUNCH MISSION**.
4. Start defending the galaxy.

No installation or build process is required.

## Browser Support

- Google Chrome
- Microsoft Edge
- Firefox
- Safari
- Mobile browsers supporting HTML5 Canvas

## Future Improvements

- Sound effects and background music
- Boss battles
- Power-ups
- Leaderboard system
- Difficulty selection
- Additional enemy varieties
- Save/load high scores

## License

This project is provided for educational and personal use.
