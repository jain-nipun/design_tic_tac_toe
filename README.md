# Design Tic Tac Toe
Created a Python Program that will play a game of Tic Tac Toe. The program will acept following parameters:
  1. --board : This will be a string of 9 characters representing the 9 cells of the 3x3 board. The string should be composed only of 'X' and 'O' to denote a player occupying that      cell or '.' to show that the cell is open. The default values is '.' as all cells are open. 
  2. --player : An optional player which must be either X or O.
  3. --cell : An optional cell which must be in the range [1-9].
 
The program will print the state of the board plus any modifications to the state made by --player and --cell along with the final outcome of the game which can either be "No winner" or "{player} has won."
When run with no arguments, it should print a blank Tic-Tac-Toe board and "No winner".
If a player tries to take an occupied cell, or a player is not in 'XO', or a cell is not in range [1-9], or a board does not represent 9 characters from '.' or 'X' or 'O', or if only --player or --cell is given, the program will throw an error with suitable error message.  
# How to run the program
Step 1 : Open the command Prompt
Step 2 : write the following syntax -> python <filePath>\<fileName> -b .XX....OO -p X -c 1
