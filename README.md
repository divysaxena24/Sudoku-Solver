🧩 Sudoku Solver in Java<br><br>
A Java-based Sudoku Solver that leverages the Backtracking Algorithm to efficiently solve any valid 9x9 Sudoku puzzle. This project is ideal for developers looking to strengthen their understanding of recursion, constraint satisfaction, and algorithmic problem-solving in Java.
<br><br><br>

🚀 Features
✅ Solves any valid 9x9 Sudoku puzzle<br>

🔄 Uses a recursive backtracking approach<br>

🖥️ Simple console-based interface<br>

🧩 Easy to understand, modify, and extend<br>

🧪 Well-structured and beginner-friendly code<br>
<br><br>
🧠 How It Works<br>
The algorithm operates using a classic backtracking technique:<br>

Locate an empty cell (represented as 0)<br>

Attempt to place digits 1–9 in the cell<br>

For each digit:<br>

Check if it's safe (i.e., not already present in the same row, column, or 3×3 sub-grid)<br>

If valid, place the number and proceed recursively<br>

If recursion fails (leads to a dead end), backtrack and try the next number<br>

If all cells are correctly filled, the puzzle is successfully solved<br>
<br><br>
📸 Example Input<br><br>
java<br>
Copy code<br>
int[][] board = {
    {5, 3, 0, 0, 7, 0, 0, 0, 0},<br>
    {6, 0, 0, 1, 9, 5, 0, 0, 0},<br>
    {0, 9, 8, 0, 0, 0, 0, 6, 0},<br>
    {8, 0, 0, 0, 6, 0, 0, 0, 3},<br>
    {4, 0, 0, 8, 0, 3, 0, 0, 1},<br>
    {7, 0, 0, 0, 2, 0, 0, 0, 6},<br>
    {0, 6, 0, 0, 0, 0, 2, 8, 0},<br>
    {0, 0, 0, 4, 1, 9, 0, 0, 5},<br>
    {0, 0, 0, 0, 8, 0, 0, 7, 9}<br>
};


📦 How to Run<br>

Clone the repository:<br>

bash<br>
Copy code<br>
git clone https://github.com/divysaxena24/Sudoku-Solver.git<br>
Open the project in your preferred IDE (e.g., IntelliJ, Eclipse)<br>

Run the Main class or the class containing the main method<br>

View the output in the console<br>


<br><br><br>

💡 Acknowledgements<br>
Inspired by the timeless logic of Sudoku puzzles<br>

A great practice project to sharpen recursion, backtracking, and Java fundamentals<br>

