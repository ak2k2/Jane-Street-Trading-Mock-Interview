# Python Dice Game Visualization
This is a project to visualize the optimal strategy to play a betting game with a 20-sided die. The game consists of 100 turns, and every turn the player has two options: to roll the die or to take the money from the casino. The goal is to maximize the player's profit in each game session. 


## Strategies Implemented
* Scenario 1: Take money or roll the dice, if you take money the dice stays fixed (you can keep the number on the table between rolls).
* Scenario 2: Take money or roll the dice, if you take money the dice disappears and must be re-rolled next turn.
* Scenario 3: (Variant of Scenario 1). If you take the $, the casino can choose to reroll the die. The casino aims to minimize your earnings.
* Gradient Descent to find the optimal player threshold for a given casino threshold.

## References
* Video Explaination: From Suby Wang via YouTube (https://www.youtube.com/watch?v=NT_I1MjckaU)
