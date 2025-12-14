# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Problem: It plays on every "board" and you can win by using multiple boards as long as it corresponds with a number in the TopLeft array
 Solution: Assigned the buttons to the corresponding arrays and the checkWinner checks every array

2. Problem: BigBoard Array doesn't update correctly
Solution: Moved the code into the for loops

4. Problem: No draw code. User can end up in a draw and nothing will happen to the small boards or big boards
Solution: I created funcions to check for draws on the small board and the big board and put them in the code

5. Problem: No code to check if board is full, user has to click a button in the board to continue playing 
Solution: created functions to check for draw and moved some code to make it work

