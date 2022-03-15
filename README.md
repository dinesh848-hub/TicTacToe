# TicTacToe

### Definition of tic-tac-toe
: a game in which two players alternately put Xs and Os in compartments of a figure formed by two vertical lines crossing two horizontal lines and each tries to get a row of three Xs or three Os before the opponent does.


![download](https://user-images.githubusercontent.com/77382339/158404707-e12f0170-9120-4695-851c-57788f67faae.png)


### Combinatorics



When considering only the state of the board, and after taking into account board symmetries (i.e. rotations and reflections), there are only 138 terminal board positions. A combinatorics study of the game shows that when "X" makes the first move every time, the game outcomes are as follows : 

91 distinct positions are won by (X)
44 distinct positions are won by (O)
3 distinct positions are drawn (often called a "cat's game.

### Strategy

A player can play a perfect game of tic-tac-toe (to win or at least draw) if, each time it is their turn to play, they choose the first available move from the following list, as used in Newell and Simon's 1972 tic-tac-toe program.

Win: If the player has two in a row, they can place a third to get three in a row.
Block: If the opponent has two in a row, the player must play the third themselves to block the opponent.
Fork: Cause a scenario where the player has two ways to win (two non-blocked lines of 2).
Blocking an opponent's fork: If there is only one possible fork for the opponent, the player should block it. Otherwise, the player should block all forks in any way that simultaneously allows them to make two in a row. Otherwise, the player should make a two in a row to force the opponent into defending, as long as it does not result in them producing a fork. For example, if "X" has two opposite corners and "O" has the center, "O" must not play a corner move to win. (Playing a corner move in this scenario produces a fork for "X" to win.)
Center: A player marks the center. (If it is the first move of the game, playing a corner move gives the second player more opportunities to make a mistake and may therefore be the better choice; however, it makes no difference between perfect players.)
Opposite corner: If the opponent is in the corner, the player plays the opposite corner.
Empty corner: The player plays in a corner square.
Empty side: The player plays in a middle square on any of the four sides.



## Project of Snapshots


## Start The Game

![image](https://user-images.githubusercontent.com/77382339/158405088-a612da31-a94a-46cb-b084-1063d7cb9902.png)

## Selecting the First Move

![image](https://user-images.githubusercontent.com/77382339/158405204-1d068b6c-b5bd-4298-bd26-95102a85cab8.png)


## Selecting the Symbols

![image](https://user-images.githubusercontent.com/77382339/158405299-41d2346d-0379-4e51-b5fe-0ef8d6382e59.png)


## Player1 win the Match

![image](https://user-images.githubusercontent.com/77382339/158405665-c3ee9f3c-f9a4-44cd-a999-ed9e66b7e8be.png)
