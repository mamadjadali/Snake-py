# Snake Game in Python
This is a simple implementation of the classic Snake game in Python using the Pygame library. The game is played on a rectangular grid, where the player controls a snake that moves around and eats apples. The objective of the game is to eat as many apples as possible without colliding with the walls or the snake's own body.
How to Play
To play the game, run the Python script snake.py. The game will start immediately, and you can use the arrow keys to control the snake's movement. The snake will move continuously in the direction you choose, and you can change its direction at any time by pressing the corresponding arrow key. The game ends when the snake collides with the walls or its own body.

# Dependencies
This implementation of the Snake game requires the following dependencies:

    Python 3.x
    pytimedinput library
    colorama library

You can install the librarys using pip:

    pip install pytimedinput
    pip install colorama

# Code Structure
The code is structured into several functions that handle different aspects of the game:

  print_field(): Prints the game field on the screen, including the snake, the walls, and the apples.
  update_snake(): Updates the position of the snake based on its current direction and whether it has eaten an apple.
  apple_collision(): Checks if the snake has collided with an apple and updates the game state accordingly.
  place_apple(): Places a new apple on the game field at a random location.
  main(): The main game loop that handles user input, updates the game state, and prints the game field.

