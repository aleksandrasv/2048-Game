# 2048-Game
Text-based version of the game of 1024, which is the same idea as the game of 2048.
When the program starts it defaults to a board size of 4x4.  It is allowed to change the board size for up to 12x12.
The goal for a 4x4 board is to get a tile with the value 1024.  Each additional increment in board size doubles the goal value, so a 5x5 board would have a goal of 2048, a 6x6 board would have a goal of 4096, and so on. 

For each move enter a direction as a letter key, as follows:

      W
    A S D
    
Where A=left,W=up, D=right and S=down.

After a move, when two identical valued tiles come together they
join to become a new single tile with the value of the sum of the
two originals. This value gets added to the score.  On each move
one new randomly chosen value of 2 or 4 is placed in a random open
square.  User input of x exits the game.

Game end when you reach max value based on the board size.

Sample Output for board 4x4:

     Welcome to 1024.
     * This program is based off of Gabriele Cirulli's game online at bit.ly/great2048 *

     For each move enter a direction as a letter key, as follows:
         W
       A S D
     where A=left,W=up, D=right and S=down.
 
     After a move, when two identical valued tiles come together they
     join to become a new single tile with the value of the sum of the
     two originals. This value gets added to the score.  On each move
     one new randomly chosen value of 2 or 4 is placed in a random open
     square.  User input of x exits the game.

      Game ends when you reach 1024.

      Score: 0
              .     .     .     4

              .     .     4     .

              .     .     .     .

              .     .     .     .

      1. Your move: a

      Score: 0
              4     .     .     .

              4     .     .     .

              .     .     .     .

              .     .     .     4

      2. Your move: s

      Score: 8
              .     .     .     .

              .     .     .     .

              .     2     .     .

              8     .     .     4

      3. Your move: a

      Score: 8
              .     .     .     .

              .     .     .     .

              2     .     4     .

              8     4     .     .

      4. Your move: a

      Score: 8
              .     .     4     .

              .     .     .     .

              2     4     .     .

              8     4     .     .

      5. Your move: s

      Score: 16
              .     .     .     4

              .     .     .     .

              2     .     .     .

              8     8     4     .

      6. Your move: a

      Score: 32
              4     .     2     .

              .     .     .     .

              2     .     .     .

             16     4     .     .

      7. Your move: x
      Thanks for playing. Exiting program...
