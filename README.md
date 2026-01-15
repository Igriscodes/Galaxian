# Galaxian Arcade Clone

A retro-inspired arcade shooter built entirely in a single HTML5 file.
##  How to Play

1. **Download** the `galaxian.html` file from this repository.
2. **Open** the file in any modern web browser (Chrome, Firefox, Edge, or Safari).
3. **Select your difficulty** and defend the galaxy!

### Controls

* **Move:** Arrow Keys or `A` / `D` keys.
* **Shoot:** Hold `SPACE`.
* **Pause:** Press `P`.

## Technical Specifications

This clone is built using **Vanilla JavaScript** and the **HTML5 Canvas API**. No external libraries or frameworks were used, ensuring lightning-fast load times and zero dependencies.

### Key Features

* **Object-Oriented Architecture:** The game engine is organized into classes (`Player`, `Enemy`, `Bullet`, `Particle`) for efficient memory management and clean state updates.
* **Dynamic Enemy AI:** Enemies utilize three distinct "diving" patterns:
* **Sine Wave:** Sweeping horizontal arcs.
* **Cosine Loop:** Tight circular maneuvers.
* **Homing:** Aggressively tracking the player's X-coordinate.


* **Particle System:** A custom physics-based explosion system handles visual effects for destroyed ships.
* **Difficulty Scaling:** The game includes three presets (Easy, Medium, Hard) that adjust dive frequency, bullet speed, and enemy velocity. Additionally, the difficulty increases incrementally as you progress through stages.
* **Responsive Rendering:** Uses `image-rendering: pixelated` via CSS to maintain that sharp, retro arcade aesthetic on high-resolution displays.

### Scoring System

* **Formation Kills:** Base points (varies by enemy color).
* **Diving Kills:** **2.5x Multiplier** for shooting enemies while they are attacking.
* **Extra Lives:** Awarded automatically upon reaching **10,000 points**.

## File Structure

* `galaxian.html`: Contains the entire game logic (JS), styling (CSS), and structure (HTML).

**Author:** [Igriscodes](https://github.com/Igriscodes)

## License
[GNU Lesser General Public License v2.1](LICENSE) - Feel free to use and modify
