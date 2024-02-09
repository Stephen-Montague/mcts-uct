# Base for testing variations of MCTS 

Plan to test several variants of Monte Carlo Tree Search (MCTS) here, including MCTS-UCT, decaying MAST, and MCTS-PUCT.


## MCTS-UCT Demo

An MCTS-UCT agent in JavaScript plays both sides of Connect 4.

The game represents a "Board" state as an array of 6 sub-arrays (length 7) of numbers (0 = empty, 1 = player1, 2 = player2), with each sub-array representing a Row, from top to bottom, of a 6x7 Board, that is, 6 Rows X 7 Columns.

Plays an entire game of Connect 4, printing each new Board with simulation results per turn, then outputs the winner, Player 1 or Player 2.

Helpful quote from the author Liu - "So that's the high-level overview of how this is going to be done. The MonteCarlo class will handle running the simulations, handling things like move choice, not caring about the rules of the game whatsoever. Conversely, the Game class will encapsulate the rules of the game, handling things like generating the legal moves for any given state, not caring about the Monte Carlo simulations whatsoever."  


## Loading Demo

Install node and run command in terminal:

  node index.js

Developed and tested on node.js 8.11.3 LTS

UCT Demo by Michael Liu, use under MIT license.
