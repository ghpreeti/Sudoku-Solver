# Visit master branch for the reference of code

# Sudoku-Solver

A web-based Sudoku solver built using HTML, CSS, and JavaScript. This application leverages the backtracking algorithm to solve Sudoku puzzles efficiently.

<img width="479" alt="image" src="https://github.com/ghpreeti/Sudoku-Solver/assets/115339754/d90d0647-2f0c-447b-a1aa-277203643133">


# Introduction
The Sudoku Solver is a web application designed to solve 9x9 Sudoku puzzles using a backtracking algorithm. Enter your puzzle into the grid, and the solver will fill in the blanks for you.

# Features
Interactive 9x9 Sudoku grid for input.
Backtracking algorithm to find solutions.
Reset and solve buttons for user interaction.
User-friendly interface with responsive design.
Error detection for invalid inputs.

# Usage
Enter the Puzzle:

Click on the cells of the grid to enter numbers.
Leave cells blank where the number is unknown.
Solve the Puzzle:

Click the Solve button to trigger the solver.
Reset the Puzzle:

Click the Reset button to clear the grid.

# How It Works
The Sudoku solver uses a backtracking algorithm to fill the grid. The algorithm works as follows:

=>Recursive Search:
Starts from the first empty cell and tries filling it with digits 1-9.
Checks if the current number is valid (i.e., no duplicates in the current row, column, or 3x3 subgrid).

=>Backtracking:
If a number fits, it moves to the next empty cell.
If no valid number is found, it backtracks to the previous cell and tries the next number.

=>Completion:
Continues this process until the grid is completely filled or no solution exists.

# Technologies Used
HTML: Structure of the web page.
CSS: Styling of the Sudoku grid and UI components.
JavaScript: Core logic for the solver and interactive features
