 M × N Zero Sum Game Solver (Swing GUI)
A Java Swing application to input and analyze a zero-sum matrix game. Supports finding the saddle point of a payoff matrix using maximin and minimax strategies.

✅ Features
GUI-based input for a matrix (up to 6×6)

Automatically generates:

Matrix A (user input)

Matrix B (negative of A)

Displays both matrices clearly

Computes Maximin (row strategy) and Minimax (column strategy)

Detects and reports Saddle Point, if any

Easy-to-use layout with buttons to generate matrix and compute result

🧠 What It Does
Accepts a zero-sum game matrix A

Computes matrix B as its negative (B = -A)

Calculates:

Maximin value from matrix A

Minimax value from matrix B

Compares their positions to determine if a saddle point exists

🖥️ How to Use
Enter the number of rows (M) and columns (N) — between 1 and 6

Click "Generate Matrix Fields" to enter matrix values

Fill out the matrix A entries

Click "Calculate"

View:

Matrix A and its negative (Matrix B)

Maximin, Minimax

Saddle point result (if found)

⚙️ Requirements
Java JDK 8 or above

Any IDE or terminal to compile and run

📌 Notes
Input values must be integers

Handles invalid input gracefully with clear error messages

Uses absolute layout for precise GUI control

Great for students learning Game Theory concepts like saddle points

