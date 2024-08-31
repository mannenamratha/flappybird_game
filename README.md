# flappybird_game
## README for Flappy Bird Game
# Overview

This Python script implements a simple Flappy Bird game using the Pygame library. The game features a bird that players control by pressing the space bar to avoid pipes and score points. The game includes functionalities for handling the bird's movement, creating pipes, updating scores, and handling game over conditions.



# Features

* Bird Movement: The bird flaps up when the space bar is pressed and falls due to gravity.

* Pipes: Randomly generated pipes that the bird must navigate through.

* Scoring System: Keeps track of the player's score and high score.

* Game Over Screen: Displays a game over message when the bird collides with a pipe or the floor/ceiling.


# Requirements
* Python 3.x

* Pygame library (install via pip install pygame)

* Image assets (place the following images in the same directory as the script):


    - img_46.png (background)

    - img_50.png (floor)

    - img_47.png (bird up)

    - img_48.png (bird down)

    - img_49.png (bird mid)

    - greenpipe.png (pipe)

    - img_45.png (game over screen)


## Installation

* Ensure Python 3.x is installed on your system.

## Controls

* Space Bar: Makes the bird flap upwards. Pressing it starts the game or restarts it after a game over.
Game Mechanics

* Gravity: The bird falls continuously unless it flaps.

 * Pipes: Move from right to left across the screen. If the bird collides with a pipe or the screen boundaries, the game ends.

* Score: Increases each time the bird successfully passes through a pair of pipes.

## Game Loop


* Event Handling: Checks for user input and updates game state based on events.

* Bird Animation: Updates bird’s position and animation based on gravity and user input.

* Pipe Movement: Moves pipes and handles collision detection.

 * Score Update: Updates the score when pipes are passed.

 * Rendering: Draws game elements on the screen and updates the display.



## Troubleshooting

* Ensure all image files are correctly placed and named.

* Make sure Pygame is correctly installed and imported.

## License

This project is open source. Feel free to modify and distribute the code as you see fit.
