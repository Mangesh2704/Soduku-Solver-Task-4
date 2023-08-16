# Sudoku Solver

This programming task has been assigned by Prodigy Infotech as part of the software development internship.

## Description

The Sudoku Solver is a Python program designed to solve Sudoku puzzles with ease. This program allows users to input an unsolved Sudoku puzzle grid, representing the puzzle's initial state. The solver employs the backtracking algorithm, a suitable technique for exploring possible solutions, to fill in the missing numbers and find the correct arrangement of numbers that satisfy the Sudoku rules. Once the puzzle is solved, the program displays the completed Sudoku grid, providing users with an instant solution to the puzzle.

## Features

- **Input Unsolved Puzzle:** Users can input the unsolved Sudoku puzzle grid, using 0 to represent empty cells.
- **Backtracking Algorithm:** The solver utilizes the backtracking technique to explore possible solutions and fill in missing numbers.
- **Sudoku Rule Validation:** Ensures that the solution adheres to the rules of Sudoku puzzles.
- **Completed Sudoku Display:** Displays the solved Sudoku grid after successfully solving the puzzle.

## How to Use

1. Clone this repository to your local machine using `git clone`.
2. Navigate to the project directory.
3. Run the program using a Python interpreter: `python sudoku_solver.py`.
4. Follow the on-screen instructions to input the unsolved Sudoku puzzle.
5. Enter the initial state of the puzzle row by row, using 0 for empty cells.
6. Once the puzzle is solved, the completed Sudoku grid will be displayed.

## Example

Suppose you have the following unsolved Sudoku puzzle:

```
Welcome to Sudoku Solver!
Please enter the Sudoku puzzle, row by row, using 0 for empty cells.
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

The program will display the solved puzzle:

```
Sudoku Solved:
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9
```

**Author:** Mangesh Pangam  
**GitHub:** [Mangesh2704](https://github.com/Mangesh2704)  
**Email:** 202103036.mangeshpkr@student.xavier.ac.in
