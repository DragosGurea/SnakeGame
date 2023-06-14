# Snake Game Project

This project is a Java-based implementation of the classic Snake Game. The game allows players to control a snake and navigate it around the screen to eat food and grow longer. The objective is to achieve the highest score without colliding with walls or the snake's own body.

## Project Files

The project consists of the following Java files:

- *DataOfSquare.java*: Defines the data structure for each square in the game grid, including its color and state.
- *KeyboardListener.java*: Listens for keyboard input to control the snake's movements.
- *Main.java*: Contains the main entry point for the game and sets up the game window.
- *SquarePanel.java*: Custom JPanel class used to represent each square in the game grid.
- *ThreadController.java*: Controls the game logic, including the snake's movement, collision detection, and food spawning.
- *Tuple.java*: Defines a tuple data structure used for storing coordinates in the game.
- *Window.java*: Represents the game window and sets up the game grid.

## Getting Started

To run the Snake Game, follow these steps:

1. Compile all the Java files in the project using a Java compiler.
2. Execute the compiled `Main` class to launch the game window.
3. Use the arrow keys on the keyboard to control the snake's movements: right, left, up, and down.
4. The game will continue until the snake collides with a wall or itself. The score will be displayed accordingly.

## Gameplay

- The snake starts with a size of 3 squares and grows longer by eating food.
- The food appears as a blue square on the grid.
- Eating the food increases the snake's length and the player's score.
- The game ends if the snake collides with a wall or itself.
- The objective is to achieve the highest score possible.
