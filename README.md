# Alien Invasion

A classic space shooter game built with Python and Pygame. Defend Earth from alien invaders by shooting them down before they reach the bottom of the screen!

## 🎮 Features

- **Fullscreen gameplay** - Immersive gaming experience
- **Ship movement** - Move your ship left and right to dodge aliens
- **Shooting mechanics** - Fire bullets to destroy alien invaders
- **Alien fleet** - Waves of aliens that move in formation
- **Collision detection** - Realistic collision system for bullets, aliens, and ship
- **Lives system** - You have 3 ships to defend Earth
- **Play button** - Click to start a new game
- **Progressive difficulty** - New fleet spawns after clearing each wave

## 📋 Prerequisites

- Python 3.6 or higher
- Pygame library

## 🎮 Controls

- **Left Arrow Key** - Move ship left
- **Right Arrow Key** - Move ship right
- **Spacebar** - Fire bullets
- **Q** - Quit game
- **Mouse Click** - Click "Play" button to start/restart game

## 🎲 Game Mechanics

- **Ship**: Your ship is located at the bottom of the screen. You can move it horizontally to avoid aliens and position yourself to shoot.
- **Bullets**: You can fire up to 3 bullets at a time. Bullets travel upward and destroy aliens on contact.
- **Aliens**: Aliens move in a fleet formation, moving horizontally and dropping down when they reach screen edges.
- **Lives**: You start with 3 ships. If an alien collides with your ship or reaches the bottom of the screen, you lose a life.
- **Game Over**: When all lives are lost, the game ends. Click "Play" to restart.

## 📁 Project Structure

```
alien_invasion/
├── AlienInvasion.py    # Main game class and game loop
├── ship.py             # Ship class for player's spaceship
├── alien.py            # Alien class for enemy invaders
├── bullet.py           # Bullet class for projectiles
├── settings.py         # Game settings and configuration
├── game_stats.py       # Game statistics (lives, score, etc.)
├── button.py           # Button class for UI elements
├── images/             # Game assets
│   ├── ship.bmp        # Ship sprite
│   └── alien.bmp       # Alien sprite
└── README.md           # This file
```

## 🛠️ Technologies Used

- **Python 3** - Programming language
- **Pygame** - Game development library

## 📝 Notes

- The game runs in fullscreen mode by default
- Image paths in `ship.py` and `alien.py` use absolute paths - you may need to update these if you move the project
- Game settings can be modified in `settings.py` to adjust difficulty, speeds, and other parameters

