
# TicTacToe-AI

Tic-Tac-Toe AI using Minimax is a recursive algorithm where the computer (our code) maximizes its chance of winning by simulating all possible moves, alternating between maximizing and minimizing players, until a terminal state (win, lose, or draw) is reached, then choosing the move that leads to the best outcome.


## Features

- Representation of the Board : You need to represent the Tic-Tac-Toe board in your code. This could be done using a 2D array, a list of lists, or any other suitable data structure.
- Minimax Algorithm : The Minimax algorithm is a recursive algorithm that explores all possible future moves of both players up to a certain depth. It alternates between maximizing and minimizing players, aiming to maximize the score for the maximizing player and minimize the score for the minimizing player.

  Here's how the Minimax algorithm works:

  - At each level of recursion, if the game has reached a terminal state (win, lose, or draw) or a specified depth limit, return the utility value of the board state.

  - If the current player is the maximizing player, recursively call the Minimax function for all possible moves, and choose the move with the maximum score.

   - If the current player is the minimizing player (e.g., 'O'), recursively call the Minimax function for all possible moves, and choose the move with the minimum score.

- Score Evaluation : In Tic-Tac-Toe, you can assign +1 for a win, -1 for a loss, and 0 for a draw. This will be done in the Minimax recursive function when it is found that game is over, after the game over state it will be checked that AI player wins or not on that basic score is going to return.
- Game Tree Traversal : Traverse the game tree using the Minimax algorithm to determine the best move for the AI player.
- Game Loop : Implement the game loop that allows the player to make moves and the AI to respond with its moves until the game is over.


## Acknowledgements

 - [Science Buddies](https://www.youtube.com/watch?v=5y2a0Zhgq0U) - This youtube helps me for understanding the basic concept of game and Algorithm
 

