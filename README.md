# sudoku-solver
Uses backtracking search to solve Sudoku puzzles

Assignment from BYU's CS 470 Artificial Intelligence class. The basic framework was created and provided by Dr. Chris Archibald.

Utilizes principles of backtracking search including:
  - Minimum-remaining values (MRV) and degree heuristic to determine which variable to be assigned next
  - Least constraining value to determine the order in which the values should be chosen
  - Forward checking detect inevitable failure early on
