# Tic-Tac-Toe Game
## Overview
This is a simple yet engaging Tic-Tac-Toe game built using Python's tkinter library. The game features a 3x3 grid where players can compete against a computer opponent. The interface is clean, intuitive, and visually appealing, with a lavender-themed board and pink highlights for winning combinations. 
Fun fact: Bill Gates created a Tic-Tac-Toe game at 13; I built this one at 12!
## Features

Player vs. Computer: Play as 'X' against a computer opponent that plays as 'O'.
Smart Computer Moves: The computer prioritizes winning moves, blocks the player's winning opportunities, and makes random moves when no strategic option is available.
Win Detection: Automatically detects and highlights winning combinations in pink.
New Game Button: Reset the board to start a fresh game at any time.
Responsive UI: Built with tkinter for a lightweight and user-friendly experience.

## How to Play

1. Run the script in a Python environment with tkinter installed.
2. The game window will display a 3x3 grid and a "New Game" button.
3. Click any empty cell to place an 'X'.
4. The computer will respond by placing an 'O' in a strategic or random position.
5. The game ends when a player wins (three identical symbols in a row, column, or diagonal) or when the board is full (a draw).
6. Click "New Game" to reset the board and play again.

## Installation

Ensure you have Python 3.x installed.
No additional libraries are required beyond the standard tkinter and random modules, which come with Python.
Copy the provided code into a .py file.
Run the script using:
```shell
python main.py
```
## Code Structure

Main Setup: Initializes the tkinter window and creates a 3x3 grid of buttons.
Game Logic:
new_game(): Resets the board for a new game.
click(row, col): Handles player moves and triggers computer moves.
check_win(smb): Checks for winning combinations for a given symbol ('X' or 'O').
check_line(a1, a2, a3, smb): Validates if three cells form a winning line.
can_win(a1, a2, a3, smb): Checks if a move can secure a win or block the opponent.
computer_move(): Implements the computer's strategy for placing 'O'.
UI Elements: Uses Button widgets with a bold Verdana font and lavender background for a clean look.

## Future Improvements

Add a difficulty setting for the computer opponent.
Implement a two-player mode.
Enhance the UI with custom themes or animations.
Add a score tracker for multiple rounds.

License
This project is open-source and available under the MIT License.
Author
Created with passion by a 12-year-old coder who beat Bill Gates' Tic-Tac-Toe age record by a year! 😎
