# N-Puzzle

N-Puzzle or sliding puzzle is a popular puzzle that consists of N tiles where N can be 8, 15, 24 and so on. The puzzle is divided into √(N+1) rows and √(N+1) columns eg. 15-Puzzle will have 4 rows and 4 columns, an 8-Puzzle will have 3 rows and 3 columns and so on. The puzzle consists of one empty space where the tiles can be moved and thus the puzzle is solved when a particular goal pattern, in this case it is a spiral puzzle.

The n-puzzle is a classic problem for modelling algorithms involving heuristics. Commonly used heuristics for this problem include counting the number of misplaced tiles and finding the sum of the taxicab distances between each block and its position in the goal configuration. It should be noted that both of these methods are admissible, in the sense that they never overestimate the number of moves that remain, which ensures optimality for certain search algorithms, such as A*.

## Goal of the project
The objective of this project is to utilise the A* search algorithm or one of its variants in order to successfully solve the N-puzzle game. The initial configuration comprises a square board of N*N cells, with one cell designated as empty and the remaining cells populated with numbers, starting from 1, that are unique within the context of the puzzle. The objective is to devise a search algorithm capable of identifying a valid sequence of moves that will lead to the final state, commonly referred to as the "snail solution," which is contingent upon the dimensions of the puzzle.

## A*
*Pros*:
-  It will always find the optimal solution provided that it exist’s and that if a heuristic is supplied it must be admissible.
-  Heuristic is not necessary, it is used to speed up the process.
-  Various heuristics can be integrated to the algorithm without changing the basic code.
-  The cost of each move can be tweaked into the algorithms as easily as the heuristic.
-  It isn’t constrained to a unidirectional search.
<br/>
*Cons*:
-  Not the best algorithm for each problem in terms of memory and processing required.
-  Uses a lot of memory since each node created has to be kept accounted for.
<br/>
*Prerequisite knowledge *:
- You need to know how to convert your problem into a graph i.e into nodes and edges.
