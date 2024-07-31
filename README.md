# PRODIGY_SD_04
Task 4 - Automatic sudoku puzzle solver

# Sudoku Solver

This is a Python program that automatically solves Sudoku puzzles using the backtracking algorithm. The program takes an input grid representing an unsolved Sudoku puzzle, fills in the missing numbers, and displays the completed Sudoku grid.

## Project Overview

The "Sudoku Solver" is a console-based application designed to solve Sudoku puzzles efficiently. It leverages the backtracking algorithm to explore possible solutions and find the correct arrangement of numbers for the puzzle. This project demonstrates the use of recursion, conditionals, and grid-based operations in Python.

## Features

- Takes an input grid representing an unsolved Sudoku puzzle.
- Uses the backtracking algorithm to solve the puzzle.
- Displays the completed Sudoku grid once solved.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository or download the `sudoku_solver.py` file to your local machine.

### Usage

1. Open a terminal or command prompt.
2. Navigate to the directory where the `sudoku_solver.py` file is located.
3. Run the program using the following command:

   ```sh
   python sudoku_solver.py
## Results

The program successfully solves Sudoku puzzles using the backtracking algorithm. It accurately fills in the missing numbers, ensuring that all Sudoku rules are followed. The solved puzzle is displayed in a readable format for the user.

### Output
Unsolved Sudoku puzzle:
5 3 . . 7 . . . .
6 . . 1 9 5 . . .
. 9 8 . . . . 6 .
8 . . . 6 . . . 3
4 . . 8 . 3 . . 1
7 . . . 2 . . . 6
. 6 . . . . 2 8 .
. . . 4 1 9 . . 5
. . . . 8 . . 7 9

Solved Sudoku puzzle:
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9

## Conclusion

The "Sudoku Solver" is a practical application of the backtracking algorithm to solve Sudoku puzzles. It demonstrates the use of recursion, conditionals, and grid-based operations in Python. This project can be extended with additional features such as a graphical user interface (GUI) for a more user-friendly experience or the ability to input custom Sudoku puzzles.
