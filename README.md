Tic Tac Toe in Python
This Python code implements a simple Tic Tac Toe game for two players.

How to Play:
Run the code: Execute the Python script.
Take turns: The game will prompt each player to enter their move by typing a number between 1 and 9, corresponding to the position on the board.
Win or Tie: The game will continue until one player gets three in a row (horizontally, vertically, or diagonally) or the board is filled. The program will declare the winner or announce a tie.

Code Structure:
board: A list representing the Tic Tac Toe board, with each element initialized as a space ' '.
print_board(): Prints the current state of the board.
player_move(icon): Tells the player to enter their move, checks if the chosen position is valid, and updates the board accordingly.
is_victory(icon): Checks if the given icon ('X' or 'O') has won the game.
while True:: The main game loop, which continues until a player wins or the game ends in a tie.
