For snake and ladder, I create a static Hashmap. Snake Map has the key as a starting point of snake and value as tailing point of snake. Similarly, ladder map has key as a lower point of ladder and value as upper point of ladder. I have initialized values of both snake and ladder map in static block.
Methods:
1). rollDice() method will generate a random number between 1 to 6.

2). calculatePlayerValue() method will calculate the position of the player based on his current position after rolling the dice.

We will first check if the new position value is greater than WINPOINT, then it will again set it to old position. In SnakeNLadder to win the race, your final position value must match the WINPOINT. It can’t be less or more.

Then it will check if there is a snake or ladder at the new position, if yes then it will change the new position of player accordingly.
