# Aim Trainer

**Aim Trainer** is a fun and interactive shooting game designed to improve your aiming skills. The game features targets that appear on the screen at random locations and sizes, which you need to hit to score points. The game tracks your performance through various metrics like hits, misses, speed, and accuracy.

## Features

- **Dynamic Targets:** Targets appear at random positions and grow/shrink over time.
- **Game Metrics:** Displays real-time statistics including elapsed time, speed, hits, misses, and accuracy.
- **Game Over Screen:** Provides a summary of your performance once the game ends.

## Installation

To run the Aim Trainer game, you'll need to have Python and Pygame installed on your system. Follow these steps to get started:

1. Clone the Repository;
2. Install Pygame;
3. Run the Game.

## Gameplay

- **Objective:** Hit as many targets as possible before you run out of lives.
- **Controls:** Click on the targets with your mouse to score points.
- **Game Over:** The game ends when you accumulate too many misses. 

## Code Overview

- **Target Class:** Manages the appearance and behavior of the targets, including growth and collision detection.
- **Main Game Loop:** Handles the game logic, including target spawning, updates, collision detection, and rendering.
- **End Screen:** Displays your performance metrics when the game ends.

## Customization

You can customize various parameters by modifying the constants in the script:

- `TARGET_INCREMENT`: Time interval (in milliseconds) for new targets to appear.
- `TARGET_PADDING`: Minimum distance from the screen edges for target placement.
- `LIVES`: Number of lives before the game ends.

## Contact

For any questions or suggestions, please contact [robson.t.vecchi@gmail.com](mailto:robson.t.vecchi@gmail.com).
