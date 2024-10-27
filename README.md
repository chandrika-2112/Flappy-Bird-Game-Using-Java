# Flappy Bird Game in Java

A simple, Java-based Flappy Bird clone built using Swing for the user interface and custom game logic. This project demonstrates basic game development principles, including collision detection, animation, and event handling.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Game Mechanics](#game-mechanics)
- [Screenshots](#screenshots)
- [Contributing](#contributing)


## Features
- **Responsive Game Mechanics**: Gravity-based movement for the bird, variable pipe placement, and collision detection.
- **Scorekeeping**: Real-time score displayed, with a "Game Over" message when the bird collides with a pipe or falls off-screen.
- **Images and Graphics**: Background, bird, and pipe images enhance the visual appeal.
- **Event Handling**: Spacebar key to control the bird's vertical movement and restart the game.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/flappy-bird-java.git
    ```
2. Open the project in your preferred Java IDE.
3. Make sure you have the required images (`flappybirdbg.png`, `flappybird.png`, `toppipe.png`, `bottompipe.png`) in the project directory.

## Usage
1. Run the `FlappyBird` class to start the game.
2. Use the `Space` key to control the bird’s movement:
    - Press the `Space` key to make the bird fly upwards.
    - Release the `Space` key to let the bird fall due to gravity.
3. Avoid hitting pipes to keep the game going and increase your score.
4. When the game is over, press `Space` again to restart.

## Game Mechanics
- **Bird Movement**: Gravity affects the bird, pulling it downward. Pressing `Space` moves the bird upward.
- **Pipe Placement**: Pipes are placed at random heights with a gap to create a dynamic obstacle course.
- **Collision Detection**: The game checks for collisions between the bird and pipes, which triggers game over.
- **Timers**:
  - **Game Loop Timer**: Controls the frame rate for smooth animation.
  - **Pipe Timer**: Periodically places new pipes to scroll across the screen.
  
## Code Structure
- `FlappyBird`: Contains the game's data, including bird and pipe properties, images, and dimensions. Manages the game logic, graphics, user input, and event handling.

## Screenshots
(![image](https://github.com/user-attachments/assets/8fd56d09-8e04-4027-8d05-11ef9f959852))

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the project.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.
