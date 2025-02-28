# Pong Game

This is a simple implementation of the classic Pong game using Python and the Turtle graphics library.

## How to Play

- Player 1 (left paddle) uses the 'w' key to move up and the 's' key to move down.
- Player 2 (right paddle) uses the 'Up' arrow key to move up and the 'Down' arrow key to move down.
- The objective is to score points by getting the ball past the opponent's paddle.

## Game Files

### main.py

This is the main file that runs the game. It sets up the game screen, paddles, ball, and scoreboard. It also contains the game loop and handles keypress events for paddle movements.

### scoreboard.py

This file defines the `Scoreboard` class, which manages the score display for both players. It updates the scores and displays them on the screen.

### ball.py

This file defines the `Ball` class, which handles the movement and collision detection of the ball. It includes methods for bouncing the ball off walls and paddles and resetting the ball's position.

### paddle.py

This file defines the `Paddle` class, which handles the movement of the paddles. It includes methods for moving the paddles up and down.

## Requirements

- Python 3.x
- Turtle graphics library (usually included with Python)

## How to Run

1. Ensure you have Python 3.x installed on your machine.
2. Clone this repository or download the files.
3. Run the `main.py` file:

```sh
python main.py
```

## Enjoy the Game!