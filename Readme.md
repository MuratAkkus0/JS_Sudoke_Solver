# Sudoku Solver Tool (Vanilla JavaScript)

This project is a **simple Sudoku solving tool** built with **vanilla JavaScript, HTML, and CSS**.  
It operates on a **hardcoded Sudoku puzzle** and analyzes each cell of a 9×9 grid according to standard Sudoku rules.

## Educational Purpose

⚠️ **This project was created for educational purposes only.**  
It was developed to practice problem-solving, algorithmic thinking, and probability-based logic using plain JavaScript.  
It is **not intended for production use**.

## Purpose

The main goal of this project is to demonstrate how Sudoku rules can be translated into code by:
- Calculating the possible numbers (1–9) for each cell
- Validating these possibilities against Sudoku constraints
- Automatically filling in cells where the probability of a number being valid is **100%**

## How It Works

- The Sudoku grid is fixed and **hardcoded**
- For each empty cell, the tool:
  - Tries numbers from **1 to 9**
  - Checks row, column, and 3×3 subgrid constraints
  - Calculates the set of valid possibilities
- If only one valid number exists for a cell, it is automatically filled

From an algorithmic perspective, the approach can be described as:
- **Constraint checking**
- Combined with a **brute-force style attempt**, since every number is tested against the rules

## Features

### Sudoku Analysis
- 9×9 Sudoku grid
- Rule validation for rows, columns, and 3×3 subgrids
- Probability calculation for valid numbers per cell

### Auto-Fill Logic
- Automatically fills cells with a single valid solution
- Leaves ambiguous cells unchanged

### Learning-Focused Design
- No dynamic Sudoku upload
- No puzzle generation
- Focused purely on understanding the solving logic

## Tech Stack

- **Vanilla JavaScript**
- **HTML**
- **CSS**

## Disclaimer

This application is a **learning project** and is intentionally kept simple.  
It does not support dynamic input, advanced solving strategies, or optimized backtracking algorithms.

---

> Future improvements could include dynamic Sudoku input, puzzle generation, advanced solving strategies, and performance optimizations.
