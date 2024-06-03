# FlappyBird
This repository contains a Flappy Bird clone implemented in Python using the Pygame library. The game involves navigating a bird through a series of pipes without colliding with them.

Getting Started

Prerequisites
Ensure you have Python and Pygame installed on your machine. You can install Pygame using pip:

sh
Copy code
pip install pygame
Running the Game
Clone the repository:
sh
Copy code
git clone https://github.com/yourusername/flappy-bird-clone.git
cd flappy-bird-clone
Run the game:
sh
Copy code
python main.py
Game Overview

Controls
Press SPACE to start the game and make the bird flap its wings.
Press R to restart the game after a game over.
Gameplay
The bird automatically falls due to gravity.
Pressing SPACE causes the bird to flap its wings and move upwards.
Navigate the bird through the gaps between the pipes to score points.
The game ends if the bird collides with the pipes or the ground.
Code Structure

Main Components
Bird Class (Bird): Manages the bird's animation, movement, and collision detection.
Pipe Class (Pipe): Manages the creation and movement of pipes, as well as scoring when the bird successfully passes through them.
Ground Class (Ground): Manages the movement of the ground to create a scrolling effect.
Main Game Loop (main): Handles the main game logic, including user input, drawing the game elements, updating the game state, and detecting collisions.
Menu Function (menu): Displays the start menu and waits for the player to start the game.
Assets
bird_down.png, bird_mid.png, bird_up.png: Images for bird animation.
background.png: Background image of the game.
ground.png: Image of the ground.
pipe_top.png, pipe_bottom.png: Images for the top and bottom pipes.
game_over.png: Image displayed when the game is over.
start.png: Image displayed on the start menu.
Key Functions
update(): Updates the position and state of game objects.
quit_game(): Handles quitting the game when the window is closed.
Customization

You can customize various aspects of the game by modifying the following:

win_height and win_width: The dimensions of the game window.
scroll_speed: The speed at which the pipes and ground move.
bird_start_position: The initial position of the bird.
Contributions

Contributions are welcome! Please fork the repository and create a pull request with your changes.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy the game! If you encounter any issues or have suggestions for improvements, feel free to open an issue.
