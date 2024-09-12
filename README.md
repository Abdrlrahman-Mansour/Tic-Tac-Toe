# Tic-Tac-Toe Game 

This project implements a **Tic-Tac-Toe** game in C++ for any board dimension (N x N), where N is an integer greater than or equal to 3. The game supports two players and includes the logic for checking winning conditions based on rows, columns, and diagonals.

## Features

- **Custom Board Size**: Play on any N x N grid (e.g., 3x3, 4x4, 5x5, etc.).
- **Two-Player Mode**: Player 1 is "X" and Player 2 is "O".
- **Winning Conditions**: 
  - Win by getting N marks in a row (horizontal, vertical, or diagonal).
- **Dynamic Board Display**: The game dynamically renders the board and updates it after each move.
- **Input Validation**: Ensures that players can only make valid moves in available spots.

## How It Works

1. **Game Setup**: 
   - The game prompts the players to enter the desired board dimension (N). For example, for a standard 3x3 game, N = 3.
   
2. **Gameplay**:
   - Players take turns entering their moves.
   - The board is updated after each move, showing the current state.
   - The game checks for a winner after every move, based on N consecutive marks either in a row, column, or diagonal.
   
3. **Winning Conditions**:
   - The game detects if a player wins by forming a horizontal, vertical, or diagonal line of N symbols.
   
4. **Draw Condition**:
   - If all positions are filled and no player has won, the game ends in a draw.

## Requirements

- **C++ Compiler**: This project requires a C++ compiler such as GCC or Clang.
- **Development Environment**: Any C++-supported IDE or text editor (e.g., Visual Studio, Code::Blocks).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Abdrlrahman-Mansour/Tic-Tac-Toe.git

