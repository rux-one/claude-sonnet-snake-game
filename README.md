# Snake Game

A classic Snake game built with HTML5 Canvas and JavaScript.

## Versions

### Basic Snake (`snake.html`)
This is the classic Snake game with TWO exciting enhancements:

- **Predator & Prey**: Enemy snakes (red) hunt both you and the food. They can bite off your tail, but you can also eat their tails! If you hit an enemy's head or body, it's game over, but if you catch their tail, you get a point and they become shorter. Enemy snakes move slightly slower than the player, giving you an advantage.

- **Shooting**: Press SPACE to shoot bullets in the direction you're moving! Bullets can destroy enemy snakes, giving you points:
  - 1 point for hitting an enemy body segment
  - 2 points for destroying an enemy that becomes too short
  - 3 points for a headshot (instantly destroying an enemy)

### Advanced Snake (`advanced-snake.html`)
A feature-rich version with multiple innovative mechanics (gravity mode, portals, evolution, enemy snakes, and more).

## How to Play
1. Open either `snake.html` or `advanced-snake.html` in any modern web browser
2. Controls for basic version:
   - Arrow keys to change direction
   - SPACE to shoot bullets
   - Q to quit
   - Eat enemy snake tails to score points
   - Shoot enemy snakes for bonus points
   - Avoid enemy snake heads and bodies
3. Controls for advanced version:
   - Arrow keys to change direction
   - Z: Activate special ability
   - X: Activate speed boost
   - SPACE: Use evolution-based abilities

## Requirements
- Any modern web browser with HTML5 support

## Changelog

### March 9, 2025
- Removed stealth segments feature to simplify gameplay
- Made enemy snakes move slower than the player (50% speed) for better balance
- Improved enemy snake AI to prevent self-collisions
- Reduced enemy spawn rate for better gameplay pacing