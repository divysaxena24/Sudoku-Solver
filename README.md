# 🧩 Sudoku Solver in Java

A Java-based **Sudoku Solver** that uses the **Backtracking algorithm** to solve any valid 9x9 Sudoku puzzle. This project is a great way to understand recursion, constraint satisfaction, and algorithmic problem-solving in Java.

---

## 🔧 Features

- Solves any valid 9x9 Sudoku puzzle
- Implements classic **Backtracking Algorithm**
- Console-based interface
- Easy to modify and extend

---

## 🧠 How it Works

The algorithm follows these steps:
1. Find an empty cell (with value 0)
2. Try placing numbers 1 through 9
3. For each number:
   - Check if it is valid (not in the same row, column, or 3x3 box)
   - If valid, place the number and recurse
   - If the recursion returns false, backtrack and try the next number
4. If all cells are filled legally, the puzzle is solved

---

DEMO 

int[][] board = {
  {5,3,0,0,7,0,0,0,0},
  {6,0,0,1,9,5,0,0,0},
  {0,9,8,0,0,0,0,6,0},
  {8,0,0,0,6,0,0,0,3},
  {4,0,0,8,0,3,0,0,1},
  {7,0,0,0,2,0,0,0,6},
  {0,6,0,0,0,0,2,8,0},
  {0,0,0,4,1,9,0,0,5},
  {0,0,0,0,8,0,0,7,9}
};

---


OUTPUT

5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7
---------------------
8 5 9 | 7 6 1 | 4 2 3
4 2 6 | 8 5 3 | 7 9 1
7 1 3 | 9 2 4 | 8 5 6
---------------------
9 6 1 | 5 3 7 | 2 8 4
2 8 7 | 4 1 9 | 6 3 5
3 4 5 | 2 8 6 | 1 7 9

----
🙌 Contributions<br>
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

✨ Acknowledgements<br>
Inspired by classic Sudoku puzzle logic<br>

Great for practice in recursion and backtracking
