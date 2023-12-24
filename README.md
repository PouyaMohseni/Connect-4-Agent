# Connect Four AI Project

## Abstract
This document presents the final project for the artificial intelligence course, focusing on implementing a Connect Four game in Python. The project encompasses the creation of two different evaluation functions for the connect four gmae based on the course lectures. Additionally, it introduces various AI algorithms, including Minimax, Minimax with Alpha-beta pruning, A*, and Neural Networks. The project also covers bonus features such as an arbitrary m*n grid, a graphical user interface (GUI), and different game modes. The following table summarizes the project:

| MiniMax | Alpha-beta pruning | Two other search approaches | Arbitrary m*n | GUI | Player vs. Player | Player vs. AI | AI vs. AI |
|---------|---------------------|-----------------------------|--------------|-----|---------------------|---------------|-----------|
| ✓       | ✓                   | ✓                           | ✓            | ✓   | ✓                   | ✓             | ✓         |

For the complete report, including detailed explanations and code implementation, refer to the [Report PDF]([link-to-report-pdf](https://drive.google.com/file/d/165qKsNC48F9CUJmH_l0MQaXiAbx4HXmI/view?usp=drive_web).


## 1. Introduction
In the game of Connect Four, players take turns placing pieces in a vertical grid with the goal of connecting four pieces in a row, vertically, horizontally, or diagonally. The project explores adversarial search algorithms, considering the complete information nature of Connect Four. The game has been theoretically solved, with the first player having a winning strategy. 

### 1.1 Search Algorithms
The section introduces search algorithms, including brute-force search and heuristics, which are essential for solving the constraint fulfillment problem. Local search methods, such as tree search algorithms, are discussed, covering exhaustive approaches like depth-first search and breadth-first search.

### 1.2 Adversarial Search
Adversarial search is explained as a scenario where an agent plans ahead while opponents plan against it. Connect Four is classified as an antagonistic, zero-sum game, considering only human intelligence and logic.

### 1.3 MiniMax Algorithm
The MiniMax algorithm is presented as a solution for adversarial search problems. The algorithm aims to maximize the agent's score while minimizing the opponent's score by assuming the opponent makes optimal moves.

### 1.4 Alpha-beta Pruning
Alpha-beta pruning is introduced as a technique to reduce the search space in the Minimax algorithm. By considering scores of sibling branches, the algorithm skips exploring branches that are not worth exploiting, significantly improving search efficiency.

## 2. Game Implementation

### 2.1 Player Interaction Modes

The Connect Four game is implemented with diverse modes, including Player vs. Player, Player vs. AI, and AI vs. AI. The game supports various board sizes, a graphical user interface (GUI), and multiple game modes.

### 2.2 Dynamic Gameplay Modes

Players can engage in different modes, including:

- **Player vs. Player:** Two human players control the game through the terminal, taking turns to make moves.

- **Player vs. AI:** Players compete against AI agents with adjustable difficulty levels and search algorithms.

- **AI vs AI:** Two AI agents play against each other, providing insights into different algorithmic approaches in autonomous gameplay.

## 3. Alternative Search Algorithms

Apart from Minimax and Alpha-beta pruning, the project introduces two alternative search algorithms: A* and Neural Networks.

### 3.1 A* Algorithm Integration

The A* algorithm is integrated with adversarial search principles, efficiently exploring the game space. It combines Minimax-style searching with A* to make strategic decisions while limiting the search depth.

### 3.2 Neural Networks for Decision-Making

A Neural Network model is implemented for game decision-making. Trained on a dataset generated through AI vs. AI gameplay, the model learns to predict optimal moves based on the current game state.

## 4. Code Insights

### 4.1 Evaluation Functions

Three distinct evaluation functions influence the decision-making process of AI algorithms. These functions provide scores based on the current position of the game, considering factors like adjacent pieces and potential opportunities. They shape the strategic decision-making process of the AI agents.


For further details and code implementation, refer to the source code files in the project repository.
