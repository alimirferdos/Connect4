
# Connect-4

This is a simple implementation of the two-player connect-4 game in C++.

![](https://raw.githubusercontent.com/alimirferdos/Connect4/master/img/board1.PNG)

When one of the users wins:
![](https://raw.githubusercontent.com/alimirferdos/Connect4/master/img/board2.PNG)



## Implementation Tips

 - The default of size of connect-4 is *7 x 6*. I've added a new row which stores the index of last empty holes. In the case of a full column, the value would be -1.
 - *board* is a two-dimensional array for keeping track of current game's status and is defaulted to all 0's in beginning
- 	user1 is shown by 1's and user2 is shown by 2's.
