# Sudoku Solver Using Backtracking

A Python implementation of a Sudoku Solver that uses the **Backtracking Algorithm** to solve a 9×9 Sudoku puzzle. The program takes an incomplete Sudoku grid as input and fills all empty cells while satisfying Sudoku constraints.

## Overview

Sudoku is a logic-based puzzle where each row, column, and 3×3 subgrid must contain the digits 1 through 9 exactly once.

This project demonstrates the use of:

* Recursion
* Backtracking
* Constraint Validation
* Problem Solving Algorithms
* Python Functions and Data Structures

The solver automatically finds a valid solution by trying possible numbers, checking constraints, and backtracking whenever an invalid state is reached.

---

## Features

* Solves standard 9×9 Sudoku puzzles
* Uses recursive backtracking
* Validates rows, columns, and 3×3 subgrids
* Displays both original and solved boards
* Written entirely in Python
* Easy to understand and modify

---

## Algorithm

The project uses the **Backtracking Algorithm**:

1. Find an empty cell (represented by 0).
2. Try numbers from 1 to 9.
3. Check whether the number is valid in:

   * Current row
   * Current column
   * Current 3×3 box
4. If valid, place the number.
5. Recursively solve the remaining puzzle.
6. If no valid number exists, backtrack and try another number.
7. Continue until the puzzle is solved.

---

## Project Structure

```text
sudoku-solver/
│
├── sudoku_solver.py
├── README.md
│
└── Sample Output
```

---

## Input Format

Empty cells are represented using **0**.

Example:

```python
board = [
    [5,3,0,0,7,0,0,0,0],
    [6,0,0,1,9,5,0,0,0],
    [0,9,8,0,0,0,0,6,0],
    [8,0,0,0,6,0,0,0,3],
    [4,0,0,8,0,3,0,0,1],
    [7,0,0,0,2,0,0,0,6],
    [0,6,0,0,0,0,2,8,0],
    [0,0,0,4,1,9,0,0,5],
    [0,0,0,0,8,0,0,7,9]
]
```

---

## Sample Output

```text
Solved Sudoku:

[5, 3, 4, 6, 7, 8, 9, 1, 2]
[6, 7, 2, 1, 9, 5, 3, 4, 8]
[1, 9, 8, 3, 4, 2, 5, 6, 7]
[8, 5, 9, 7, 6, 1, 4, 2, 3]
[4, 2, 6, 8, 5, 3, 7, 9, 1]
[7, 1, 3, 9, 2, 4, 8, 5, 6]
[9, 6, 1, 5, 3, 7, 2, 8, 4]
[2, 8, 7, 4, 1, 9, 6, 3, 5]
[3, 4, 5, 2, 8, 6, 1, 7, 9]
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/sudoku-solver.git
```

### Navigate to Project Directory

```bash
cd sudoku-solver
```

### Run the Program

```bash
python sudoku_solver.py
```

---

## Learning Outcomes

This project helped in understanding:

* Recursive Function Calls
* Backtracking Techniques
* Search Algorithms
* Constraint Satisfaction Problems
* Python Programming Fundamentals

---

## Future Improvements

* GUI using Tkinter
* Sudoku Puzzle Generator
* User Input Support
* Difficulty Levels
* Visualization of Solving Process

---

## Technologies Used

* Python 3
* Recursion
* Backtracking Algorithm

---

## Author

Developed as a learning project to explore recursion, backtracking, and algorithmic problem solving using Python.
