# Ceng-Checkers

![poster](https://github.com/basbugahmet/Ceng-Checkers/blob/main/poster.jpg)


## General Information

The game is played on an 8x8 board with human (x) and computer (o) players. The human player starts the game, and the goal is to move all 9 pieces across the board and into their home area, which is the opposing 3x3 area.


## Game Rules

### Players

The players of the game are human (x) and computer (o), and the human player starts the game.

### Game Board

The game is played on an 8x8 board. Human player has x pieces in the bottom right 3x3 area of the board and computer player has o pieces in the top left 3x3 area.

### Game Playing Rules

All the moves are in 4 directions, diagonal moves cannot be used.

There are two move types for a player in each turn: either a step or jump(s).

-   Step: If adjacent square of a piece in any direction (left, right, up or down) is empty, that piece can step into the empty square.
-   Jump: A piece can jump over only a single adjacent piece (his/her or opponent's). Jumping over 2 or more pieces or distant pieces is not allowed.

Jumping operations can be continued with successive jumps (called jump chain) if possible, in the same turn. On the contrary, step operation is a single one. There is no capturing in this game, so all pieces remain active during the game.

For each step or jump operation, the human player firstly chooses the piece to move, then chooses the target square of the piece.


## How to Play

To play CENG Checkers, follow these steps:

1.  Clone the repository to your local machine.
2.  Open the terminal and navigate to the directory where you cloned the repository.
3.  Run the following code to start the game:
4.  Use the arrow keys to move the cursor and select a piece to move.
5.  Press the 'Z' key to choose the selected piece.
6.  Use the arrow keys to move the cursor and select the target square.
7.  Press the 'X' key to choose the target square.
8.  If there is no successive jumps, end the move by pressing the 'C' key. If the player wants to jump again, go to step 4.
