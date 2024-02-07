# Tic-Tac-Toe Game with Minimax Algorithm and Alpha-Beta Pruning

## Overview
This Python script implements the classic Tic-Tac-Toe game with an AI opponent using the Minimax algorithm with alpha-beta pruning. Tic-Tac-Toe is a two-player game where players take turns marking spaces in a 3x3 grid with their respective symbols (X or O) with the goal of getting three of their symbols in a row, column, or diagonal.

## Code Description
1. **Game Logic Functions**: The script defines functions for game initialization, player moves, determining the winner, checking for terminal conditions, and calculating the utility of game states.
2. **Minimax Algorithm with Alpha-Beta Pruning**: The `max_value` and `min_value` functions implement the Minimax algorithm recursively with alpha-beta pruning to determine the best move for the AI player.
3. **Game Loop**: The `play_game` function runs the main game loop, allowing players to make moves and the AI opponent to respond using the Minimax algorithm.
4. **Utility Functions**: Utility functions such as drawing the game board, checking for available actions, and obtaining the next player's turn are defined to facilitate gameplay.

## How to Play
1. Run the script and follow the on-screen instructions.
2. Enter the row and column numbers (0-indexed) to place your symbol (X) on the game board.
3. The AI opponent (O) will make its move using the Minimax algorithm.
4. Continue making moves until one player wins or the game ends in a draw.

## Files
- `tic_tac_toe.py`: Python script containing the Tic-Tac-Toe game implementation.

## Prerequisites
- Python 3.x
- Basic understanding of Python programming and game development concepts.

## Notes
- The AI opponent uses the Minimax algorithm with alpha-beta pruning to make optimal moves, ensuring a challenging gameplay experience.
- Feel free to modify the code or experiment with different strategies to improve the AI player or add additional features to the game.

Enjoy playing Tic-Tac-Toe against the AI opponent!
