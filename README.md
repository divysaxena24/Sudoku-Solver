# 🧩 Sudoku Solver in Java

A **Java-based Sudoku Solver** that leverages the **Backtracking Algorithm** to efficiently solve any valid 9x9 Sudoku puzzle.  
This project is ideal for developers looking to strengthen their understanding of **recursion**, **constraint satisfaction**, and **algorithmic problem-solving** in Java.

---

## 🚀 Features

- ✅ Solves any valid **9x9 Sudoku puzzle**
- 🔄 Uses a **recursive backtracking approach**
- 🖥️ Simple **console-based interface**
- 🧩 Easy to understand, modify, and extend
- 🧪 Well-structured and **beginner-friendly** code

---

## 🧠 How It Works

The algorithm operates using a classic backtracking technique:

1. **Locate an empty cell** (represented as `0`)
2. **Attempt to place digits** from `1` to `9` in that cell
3. For each digit:
   - Check if it's **safe** (i.e., not already present in the same row, column, or 3×3 sub-grid)
   - If **valid**, place the number and **recursively solve** the remaining puzzle
   - If recursion fails (i.e., leads to a dead end), **backtrack** and try the next digit
4. If all cells are correctly filled, the puzzle is successfully solved ✅

---

## 📸 Example Input

```java
int[][] board = {
    {5, 3, 0, 0, 7, 0, 0, 0, 0},
    {6, 0, 0, 1, 9, 5, 0, 0, 0},
    {0, 9, 8, 0, 0, 0, 0, 6, 0},
    {8, 0, 0, 0, 6, 0, 0, 0, 3},
    {4, 0, 0, 8, 0, 3, 0, 0, 1},
    {7, 0, 0, 0, 2, 0, 0, 0, 6},
    {0, 6, 0, 0, 0, 0, 2, 8, 0},
    {0, 0, 0, 4, 1, 9, 0, 0, 5},
    {0, 0, 0, 0, 8, 0, 0, 7, 9}
};




📦 How to Run

Clone the repository

bash
Copy code
git clone https://github.com/divysaxena24/Sudoku-Solver.git


