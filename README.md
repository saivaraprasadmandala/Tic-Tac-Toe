
# 🎮 Tic-Tac-Toe Game — Java Console Application

A simple console-based Tic-Tac-Toe game built in Java for two players. Players take turns to mark `X` or `O` on a 3x3 grid until one player wins or the board is full.

---

## 💡 Features

- ✅ Two-player console-based gameplay.
- ✅ Input validation for each move.
- ✅ Detects winner in:
  - Rows
  - Columns
  - Diagonals
- ✅ Clear and modular code using Java functions.

---

## 📌 Game Flow

1. The board is initialized as a 3x3 empty grid.
2. Players `X` and `O` alternate turns.
3. Players input two integers for **row** and **column** positions:

Player X enter: 0 1

4. If the selected cell is occupied, the program notifies:
 Invalid move. Try again!

5. After each valid move, the game checks for a winner.
6. If a player wins: Player X has won!
7. The final state of the board is printed once the game ends.

---

## 💻 Code Structure

| Method                  | Description                                               |
|--------------------------|-----------------------------------------------------------|
| `main()`                 | Controls game loop, player turns, and move validation.    |
| `haveWon(board, player)` | Checks all rows, columns, and diagonals for a win.         |
| `printBoard(board)`      | Prints the current state of the game board.                |

---

## 📂 How to Run

1. Copy the code into a file named `Main.java`.
2. Open terminal and navigate to the file directory.
3. Compile the program:
```bash
javac Main.java

4.Run the compiled class:
java Main
```
## Sample Output
  |   |   
  |   |   
  |   |   
Player X enter: 0 0

X |   |   
  |   |   
  |   |   
Player O enter: 1 1

X |   |   
  | O |   
  |   |   

... and so on until one player wins!

