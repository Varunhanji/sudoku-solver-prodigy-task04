# 🧩 Sudoku Solver

This project is a **Sudoku Solver** developed as part of **ProDigy InfoTech Internship - Task 04**.

---

## 📌 Project Description

The Sudoku Solver is a program that automatically solves a given Sudoku puzzle using an algorithmic approach.

The program takes an incomplete 9x9 Sudoku grid as input and fills in the missing numbers while ensuring all Sudoku rules are followed.

---

## 🚀 Features

- 🧠 Solves standard 9x9 Sudoku puzzles
- 🔄 Uses Backtracking algorithm
- 📥 Accepts partially filled grids as input
- 📤 Displays the completed Sudoku grid
- ⚡ Efficient and accurate solution finding

---

## 🧠 Algorithm Used

### Backtracking

Backtracking is a recursive algorithm that:

1. Finds an empty cell in the grid
2. Tries numbers from 1 to 9
3. Checks if the number is valid:
   - Not repeated in the row
   - Not repeated in the column
   - Not repeated in the 3x3 subgrid
4. If valid, places the number and continues
5. If no number works, it backtracks to the previous step

---

## 🧮 Example Input
