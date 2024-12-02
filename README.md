# Asteroids_pygame
# Asteroids Game

This project is a basic implementation of the classic **Asteroids** game using the Pygame library in Python. The player controls a spaceship, dodges asteroids, and scores points by shooting them.

---

## Features

- **Player Controls:**
  - Rotate the spaceship left and right.
  - Propel the spaceship forward with thrust.
  - Shoot bullets to destroy asteroids.
- **Asteroids:**
  - Multiple moving asteroids with randomized directions.
  - Colliding with an asteroid ends the game.
- **Scoring:**
  - Points are awarded for destroying asteroids.
  - Display of the player's score during gameplay.
- **Game Over Screen:**
  - A "GAME OVER" message is displayed when the player loses.
- **Sound Effects:**
  - Background music.
  - Sound effects for shooting missiles, thrusting, and explosions.

---

## Requirements

- Python 3.x
- Pygame library

To install Pygame, run:
```bash
pip install pygame
```

---

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd asteroids-game
   ```

2. Ensure the following folder structure:
   ```
   .
   |-- images
   |   |-- bg.jpg
   |   |-- debris2_brown.png
   |   |-- ship.png
   |   |-- ship_thrusted.png
   |   |-- asteroid.png
   |   |-- shot2.png
   |   |-- explosion_blue.png
   |
   |-- sounds
   |   |-- missile.ogg
   |   |-- thrust.ogg
   |   |-- explosion.ogg
   |   |-- game.ogg
   |
   |-- asteroids.py
   ```

3. Run the game:
   ```bash
   python asteroids.py
   ```

---

## Controls

- **Arrow Keys:**
  - `Left/Right` to rotate the spaceship.
  - `Up` to thrust forward.
- **Spacebar:**
  - Shoot bullets.

---

## Project Structure

- **`asteroids.py`** - Contains the main game logic and functionality.
- **`images/`** - Contains all the images used for the background, spaceship, asteroids, bullets, and explosions.
- **`sounds/`** - Contains all the sound effects and background music for the game.

---

## Future Enhancements

- Add levels with increasing difficulty.
- Implement a high-score tracking system.
- Add more spaceship features (e.g., shields, power-ups).
- Create a pause and restart functionality.

---

## License

This project is open-source and free to use. Feel free to contribute or modify as needed.

---

## Acknowledgments

- **Pygame** - For providing the tools to create this game.
- Inspired by the classic arcade game **Asteroids**.
