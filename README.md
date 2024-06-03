# FlappyBird
This repository contains a Flappy Bird implemented in Python using the Pygame library. The game involves navigating a bird through a series of pipes without colliding with them.

**Getting Started**

_Prerequisites_
Ensure you have Python and Pygame installed on your machine. You can install Pygame using pip:

`pip install pygame`


**Running the Game**
_Clone the repository:_

`git clone https://github.com/satviksharmase/FlappyBird.git`
`cd flappy-bird-clone`

_Run the game:_

`python main.py`

**Game Overview**

_Controls_
1. Press SPACE to start the game and make the bird flap its wings.
2. Press R to restart the game after a game over.
_Gameplay_
1. The bird automatically falls due to gravity.
2. Pressing SPACE causes the bird to flap its wings and move upwards.
3. Navigate the bird through the gaps between the pipes to score points.
4. The game ends if the bird collides with the pipes or the ground.
   
**Code Structure**

_Main Components_
1. Bird Class (Bird): Manages the bird's animation, movement, and collision detection.
2. Pipe Class (Pipe): Manages the creation and movement of pipes, as well as scoring when the bird successfully passes through them.
3. Ground Class (Ground): Manages the movement of the ground to create a scrolling effect.
4. Main Game Loop (main): Handles the main game logic, including user input, drawing the game elements, updating the game state, and detecting collisions.
5. Menu Function (menu): Displays the start menu and waits for the player to start the game.
_Assets_
1. bird_down.png, bird_mid.png, bird_up.png: Images for bird animation.
2. background.png: Background image of the game.
3. ground.png: Image of the ground.
4. pipe_top.png, pipe_bottom.png: Images for the top and bottom pipes.
5. game_over.png: Image displayed when the game is over.
6. start.png: Image displayed on the start menu.

**Key Functions**
1. update(): Updates the position and state of game objects.
2. quit_game(): Handles quitting the game when the window is closed.
**Customization**

You can customize various aspects of the game by modifying the following:

1. win_height and win_width: The dimensions of the game window.
2. scroll_speed: The speed at which the pipes and ground move.
3. bird_start_position: The initial position of the bird.
**Contributions**

Contributions are welcome! Please fork the repository and create a pull request with your changes.

Enjoy the game! If you encounter any issues or have suggestions for improvements, feel free to open an issue.
😁
