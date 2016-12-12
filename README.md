# Gaming-Array

Andy loves playing games. He wants to play a game with his little brother, Bob, using an array, , of  distinct integers. The rules are as follows:

Bob always plays first and the two players move in alternating turns.
In a single move, a player chooses the maximum element currently present in the array and removes it as well as all the other elements to its right. For example, if , then it becomes  after the first move because we remove the maximum element (i.e., ) and all elements to its right (i.e.,  and ).
The modifications made to the array during each turn are permanent, so the next player continues the game with the remaining array. The first player who is unable to make a move loses the game.
Andy and Bob play  games. Given the initial array for each game, can you find and print the name of the winner on a new line? If Andy wins, print ANDY; if Bob wins, print BOB.


Sample Input:

2
5
5 2 6 3 4
2
3 1

number of games
number of elements in board
elements of board

output:

The name of winner should be printed on to the screen
