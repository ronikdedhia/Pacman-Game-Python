![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)
![Pygame](https://img.shields.io/badge/Library-Pygame-green?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)

# Pac-Man Game (Python)

A faithful Pac-Man arcade clone written in Python using Pygame. Navigate the player through a maze-like environment, collect all the dots, and avoid the Slime enemies. The game features a main menu, sound effects, a scoring system, and a game-over screen.

## Features

- Classic Pac-Man maze grid defined by an environment map (horizontal + vertical path blocks)
- Dot collection — dots are placed at every valid grid cell
- Enemy AI — 8 Slime enemies patrol the maze with directional movement
- Scoring — score increments as dots are collected
- Sound effects — Pac-Man movement sound and game-over sound
- Main menu with **Start**, **About**, and **Exit** options
- Game-over detection via player–enemy collision
- 30 FPS game loop with clean event handling

## Controls

| Key | Action |
|-----|--------|
| Arrow Keys | Move player (Up / Down / Left / Right) |
| Enter | Confirm menu selection |
| Close Window | Quit game |

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Python 3.7+ |
| Game Engine | Pygame |
| UI Dialogs | Tkinter (messagebox) |
| Audio | Pygame mixer (`.ogg` files) |
| Sprites | Custom PNG images |

## Getting Started

### Prerequisites

```bash
pip install pygame
```

### Run the Game

```bash
python main.py
```

All assets (`player.png`, `slime.png`, `walk.png`, `explosion.png`, `pacman_sound.ogg`, `game_over_sound.ogg`) must be in the same directory.

## File / Folder Structure

```
Pacman-Game-Python/
├── main.py              # Entry point — initializes Pygame and game loop
├── game.py              # Game logic: menu, maze, dots, enemies, scoring
├── player.py            # Player sprite and movement
├── enemies.py           # Slime enemy sprites and AI
├── player.png           # Player sprite
├── slime.png            # Enemy sprite
├── walk.png             # Walk animation asset
├── explosion.png        # Explosion effect
├── pacman_sound.ogg     # Movement audio
└── game_over_sound.ogg  # Game-over audio
```

## Demo

| Preview | Description |
|---------|-------------|
| _(demo GIF placeholder)_ | Gameplay — collecting dots and avoiding enemies |
| _(screenshot placeholder)_ | Main menu (Start / About / Exit) |
| _(screenshot placeholder)_ | Game-over screen with score |

## License

MIT License — see [LICENSE](LICENSE) for details.
