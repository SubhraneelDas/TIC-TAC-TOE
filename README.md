# TIC-TAC-TOE
This is a basic implementation of the classic Tic Tac Toe game in the C programming language. The game is played between two players, where each player takes turns to mark an X or an O in a 3x3 grid. The goal is to get three of your marks in a row, either horizontally, vertically, or diagonally.

The program starts by initializing the grid with the numbers 1 to 9. Then, a do-while loop is used to take turns between the two players until a win or draw condition is met. The loop uses the checkwin function to determine the game's current status.

The board function is used to draw the Tic Tac Toe grid with the current state of the game. It does this by printing the values in the square array in the appropriate format.

The checkwin function checks the current state of the grid to determine if a win or draw condition has been met. It does this by checking each row, column, and diagonal of the grid for matching values.

If a win condition is met, the loop is broken, and the winner is declared. If a draw condition is met, the loop is broken, and the game is declared a draw.

Overall, this is a simple and straightforward implementation of Tic Tac Toe in C, suitable for beginners looking to practice their programming skills.
