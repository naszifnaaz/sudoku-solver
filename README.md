# Sudoku Solver
This is a sudoku solver created using Pygame in python using the backtracking algorithm. 

![image](https://img.freepik.com/free-vector/hand-drawn-flat-design-sudoku-game-design_23-2149288593.jpg?w=2000)

## Abstract

Sudoku is a logic-based, combinatorial number-placement puzzle. In classic sudoku, the objective is to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids that compose the grid contains all of the digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution.

The solver is created using the backtracking algorithm, solving the puzzle recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point of time

## Requirements

+ Install [Python 3.x](https://www.python.org/download/releases/)
+ Install [PyGame 1.9x](https://pipenv.pypa.io/en/latest/)

## How to Run ?

1. Clone the repository:

       $ https://github.com/naszifnaaz/sudoku-solver.git
    or download as zip and extract.
    
2. In the root directory, run:

          $  python sudoku.py

## How to Play ?

+ Click a box to input a number.
+ Press [Enter] to confirm the number.
+ Press [Delete]  to remove the number.
+ To solve the sudoku automatically, press [SPACE] and let the algorithm do that for you.

## Future Possibilities

At the moment we only have one sudoku board, we can create an external file with many distinct boards, which the program can access randomly.
