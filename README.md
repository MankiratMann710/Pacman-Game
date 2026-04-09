# Pacman 👾

A fully playable Pacman clone built with Python and Pygame.

## Features
- Classic Pacman gameplay with all 4 ghosts: Blinky, Pinky, Inky, and Clyde
- Each ghost has unique chase/movement AI
- Power-up system — eat big dots to turn ghosts vulnerable and score combo multipliers
- Animated player sprite with directional frames
- Full collision detection against a tile-based board
- Screen wrap-around on left/right tunnels
- Lives system, score tracking, game over and win states
- Press `Space` to restart after game over

## Controls
| Key | Action |
|-----|--------|
| ← → ↑ ↓ | Move Pacman |
| Space | Restart (after game over/win) |

## Project Structure
```
├── pacman.py            # Main game loop, player & ghost logic
├── board.py             # Tile map definition (33x30 grid)
└── assets/
    ├── player_images/   # Directional Pacman sprites (1-4)
    └── ghost_images/    # Ghost sprites (red, pink, blue, orange, powerup, dead)
```

## Requirements
pip install pygame

## Run
python pacman.py

## Built With
- Python 3
- Pygame

## Demo
[![Pacman Demo]([https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID](https://youtube.com/shorts/7zfSZHZeoTo?feature=share))
