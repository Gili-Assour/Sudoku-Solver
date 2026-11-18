
# Sudoku Solver in C

This project implements a Sudoku solver in C using dynamic memory allocation and a recursive backtracking algorithm.

## Features

- Supports NxN Sudoku boards (e.g., 4x4, 9x9)
- Efficient matrix representation using dynamic memory allocation
- Validation of rows, columns, and sub-grids
- Full solution using backtracking

## Algorithm

The solver is based on a backtracking approach:

1. Locate an empty cell in the grid.
2. Attempt to place a valid value (1 to N).
3. Recursively continue solving the board.
4. Backtrack if a dead-end is reached.

## Technologies

- C
- Dynamic Memory Allocation
- Recursion

## How to Run

Compile:
```bash
gcc sudoku_solver.c -o sudoku
```

Run:
```bash
./sudoku
```

## Output

The solved Sudoku board is printed to the console.
  
