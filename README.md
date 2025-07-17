# Tic Tac Toe AI

This is a Python-based Tic Tac Toe game featuring an intelligent AI opponent. The game is developed using the Pygame library for graphics and user interaction, and the AI is implemented using the Minimax algorithm, ensuring an optimal playing experience.

## Features

* Single-Player Mode: Play against a challenging AI opponent.
* Minimax AI: The AI uses the Minimax algorithm to make optimal moves, making it a formidable opponent.
* Interactive GUI: Built with Pygame for a clear and responsive graphical interface.
* Game State Detection: Automatically detects wins, losses, and ties.
* Restart Functionality: Easily restart the game at any point.

## Technologies Used

* Python: The core programming language.
* Pygame: A set of Python modules designed for writing video games.
* NumPy: Used for efficient array operations, particularly for managing the game board.

## How to Play

1.  **Launch the game:** Run the `main.py` file.
2.  **Player 1 (You):** You play as circles. Click on any empty square on the 3x3 grid to place your mark.
3.  **AI Opponent:** The AI plays as crosses and will make its move immediately after yours.
4.  **Objective:** Be the first to get three of your marks in a row, column, or diagonal to win.
5.  **Game End:** The game concludes when a player wins or when all squares are filled, resulting in a tie.
6.  **Restart:** Press the `R` key on your keyboard at any time to restart the game.

## Installation and Setup

To run this game, you need to have Python installed on your system.
You also need to install the required Python libraries: `pygame` and `numpy`.

1.  **Install Dependencies:**
    Open your terminal or command prompt and run the following commands to install Pygame and NumPy:

    ```bash
    pip install pygame
    pip install numpy
    ```

2.  **Run the game:**
    Navigate to the directory where `main.py` is located and execute the game using Python:

    ```bash
    python main.py
    ```
