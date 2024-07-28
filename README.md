# AI Project - Pentago Game with Minimax Algorithm

## Overview
This project implements the Pentago game with an AI opponent using the Minimax algorithm enhanced with Alpha-Beta pruning. Pentago is a two-player strategy game where the objective is to get five of your pieces in a row on a 6x6 board divided into four 3x3 quadrants.

## Game Mechanics
- **Placement**: Players take turns placing two pieces on the board.
- **Rotation**: After placing pieces, players rotate one of the quadrants 90 degrees left or right.
- **Winning**: The first player to align five pieces in a row (horizontally, vertically, or diagonally) wins.

## Input Format
Players input their moves in the format: `A/B C/D X`
- `A/B` and `C/D`: Positions to place the two pieces (quadrant/cell).
- `X`: Rotation operation (quadrant and direction).

### Example
`1/1 2/5 3R`
- Place pieces in the 1st cell of the 1st quadrant and the 5th cell of the 2nd quadrant.
- Rotate the 3rd quadrant 90 degrees to the right.

## AI Implementation
The AI uses the Minimax algorithm with Alpha-Beta pruning to determine optimal moves by:
1. Generating possible moves.
2. Evaluating board states recursively.
3. Selecting the best move to minimize potential losses.

## Components
- **Move Class**: Represents a move in the game.
- **Node Class**: Represents a node in the game tree.
- **AI Class**: Implements the AI logic.
- **Player Class**: Represents a player.
- **GameBoard Class**: Manages the game state.

## Running the Project
1. Clone the repository.
2. Navigate to the project directory.
3. Run the game using Python.

## Live Demo
Check out the live demo of the project [here](https://kiana8181.github.io/AI-Project-Minimax-Algorithm-/).
