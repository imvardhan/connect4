# CONNECT FOUR
Understanding the working of Minmax Algorithm and Alpha Beta pruning by building the game Connect Four

## Overview

The Minimax algorithm with Alpha-Beta pruning was applied to optimize gameplay in Connect Four, a two-player, zero-sum game where players aim to align four discs of their color vertically, horizontally, or diagonally. This algorithm is designed to systematically explore potential moves by recursively evaluating game states, alternating between maximizing the score for the current player and minimizing the score for the opponent.

## Description

Minimax with Alpha-Beta pruning is a strategic algorithm used in Connect Four to optimize decision-making. It evaluates potential moves by recursively exploring game states, alternating between maximizing the current player's score and minimizing the opponent's score. Alpha-Beta pruning enhances efficiency by discarding unfruitful branches of the game tree, based on bounds (alpha and beta) that represent the best-known scores. This approach balances exploration and exploitation, ensuring competitive performance by efficiently navigating the game's possibilities.

## Files

- **connect4_with_ai.py**: This folder consists of the code built to run the algorithms.


- **ConnectFour.pdf**: A detailed report in IEEE format of the project.


## Dependencies

- Python 3.x
- pygame
- NumPy
- Matplotlib
- sys
- math

## Contribution

Contributions to the project are welcome! Feel free to fork the repository, make improvements, and submit pull requests