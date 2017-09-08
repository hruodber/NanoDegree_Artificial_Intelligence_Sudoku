# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: we first identified inside a unit boxes if there are any replicated number of two digits and we made
sure those digits were removed from all other boxes of that unit , because a box belongs to more
than one unit we affected with this action other units so it can be said the constrain local to a unit
is affecting other units.

# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: When we add both diagonals as units to be processed by the algorithm in the unit list we are also establishing
additional constrains because local restriction in the diagonals will affect other units.


