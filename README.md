# Tic Tac Toe in Java  

A simple implementation of the **Tic Tac Toe** game in Java, where two players take turns placing their mark (X or O) on a 3x3 board. The game ends when one player gets three marks in a row, column, or diagonal, or when the board is filled with marks without a winner.  

---

## Usage  

1. Run the `TicTacToe` class in your Java IDE or from the command line.  
2. The game will display an empty board and prompt the first player to enter their move.  
3. Players enter the row and column numbers (0-2) for their mark.  
4. The board updates after each move, and the next player is prompted to make their move.  
5. The game continues until:  
   - There is a winner.  
   - The board is filled, resulting in a draw.  
6. At the end of the game, the program will display the final board and exit.  

---

## Implementation  

- The board is represented by a **2D char array**, with the following conventions:  
  - `'-'`: Empty spot  
  - `'X'`: Player 1's mark  
  - `'O'`: Player 2's mark  

- **Game Logic**:  
  - The program checks for wins by evaluating rows, columns, and diagonals for matching marks.  
  - A draw is determined when all spots are filled without a winner.  

- **Error Handling**:  
  - Players cannot place their mark on an already occupied spot.  
  - Players cannot make moves outside the board boundaries.  

---

## Contributing  

Contributions are welcome! You can help improve this project by:  
- Suggesting enhancements or new features.  
- Fixing bugs.  
- Optimizing the code.  

To contribute:  
1. Fork the repository.  
2. Create a new branch for your changes.  
3. Submit a pull request detailing your modifications.  

---

Feel free to explore, modify, and share this project! 😊  
