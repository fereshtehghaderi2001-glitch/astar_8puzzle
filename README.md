8‑Puzzle Solver using A* Search Algorithm
This project implements an A* search algorithm to solve the classic 8‑puzzle problem.

It compares two different heuristic functions:

Misplaced Tiles Heuristic
Manhattan Distance Heuristic
The algorithm starts from a randomly generated initial state and attempts to reach a predefined goal state.
----------------------------------------------------------------------
Features
Complete implementation of the A* (A-star) search algorithm
Two heuristic functions:
   -Misplaced Tiles: Counts tiles that are not in the correct position
   -Manhattan Distance: Sum of Manhattan distances for all misplaced tiles
random initial state generator (based on valid backward moves from goal)
move cost support (with custom cost per move)
tracks:
   -total execution time
   -total path cost
   -number of visited/expanded nodes
clean and modular helper functions
----------------------------------------------------------------------
Notes
The Manhattan heuristic is generally more efficient and produces fewer expanded nodes.
Move costs in moves can be adjusted to experiment with weighted puzzles.
