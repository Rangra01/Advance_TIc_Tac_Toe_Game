Tic-Tac-Toe_Game (C Language)

Game Controls
- Input row (1 to 3)numbers and column (1 to 3) numbers  when prompted.
- After each round, choose whether to play again.

Features
- Play against an intelligent computer opponent.
- Two difficulty modes:
- Standard Mode: Basic AI with random moves and simple logic.
- God Mode: Hard AI that uses perfect strategy.
- Keeps track of the score (Player wins, Computer wins, and Draws).
- Random starting player (Player or Computer).
- Intelligent move selection with blocking and winning strategies.
- Clean board rendering and cross-platform support.

File Structure
tic-tac-toe/
-> tictactoe.c # Main source code for the game
-> README.md # Project overview and instructions

AI Logic
- Phase 1: Try to win in the current move.
- Phase 2: Try to block the player if they are about to win.

- God Mode Enhancements:
- Takes center if available.
- Prioritizes corners.
- Fallback: Selects the first available space.

Getting Started
Prerequisites:
- A C compiler like gcc.
Compilation:
$ gcc main.c -o tictactoe
Running:
$ ./tictactoe
or on Windows:
$ tictactoe.exe


Function Overview

play_game() - Manages a full round of the game
player_move() - Takes player input
computer_move() - Computer decision-making logic
check_win() - Checks if a player has won
check_draw() - Checks if the game is a draw
print_board() - Displays the current board
input_difficulty() - Allows user to choose difficulty level
clear_screen() - Clears the terminal screen

By-Rahul

This game was coded in C as a beginner project to improve understanding of AI logic, control flow, and user interaLicense
