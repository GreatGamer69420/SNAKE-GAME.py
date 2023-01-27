Snake Game
This code creates a simple terminal-based Snake game where the player controls a snake to move around the grid and eat food to increase the score. The game ends when the snake hits a wall or itself.

Getting Started
The game can be run by executing the code in a Python environment. The player can control the snake using the arrow keys to move up, down, left, and right. The game will continue until the snake hits a wall or itself.

Game Rules
The snake starts at a random position on the grid
The snake's food also starts at a random position on the grid
The snake can move up, down, left, and right
The snake's goal is to reach the food
If the snake reaches the food, the food will be re-spawned at a random position and the player's score will increase
If the snake hits a wall or itself the game is over
Code Structure
The code is structured in two parts.
The first part is the game loop, which continues until the game is over. The game loop consists of the following steps:

Clearing the terminal screen
Creating a new grid
Adding the walls to the grid
Adding the snake and food to the grid
Printing the grid
Printing the score
Getting user input for the next move
Updating the snake position based on the move
Checking if the snake hit the wall or itself
Checking if the snake ate the food
Adding the new snake position to the body
Waiting for a bit before the next move
The second part is a modified version of the first part. The modifications include

Grid size changed from 11 to 15
The Walls, Snake, and Food are represented by different characters "#", "S", and "F" respectively
The game loop is similar to the first part with slight modifications
Requirements
Python 3
A terminal window to run the code
Built With
Python
Standard Library modules : os, random, time
Note
The code uses 'cls' command on Windows and 'clear' command on other platforms to clear the terminal screen. In case it doesn't work in your system, you can replace it with any other command or function that clears the terminal screen.
