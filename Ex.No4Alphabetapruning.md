# Ex.No: 4   Implementation of Alpha Beta Pruning 
### DATE:30-08-2025                                                                            
### REGISTER NUMBER : 212222040172
### AIM: 
Write a Alpha beta pruning algorithm to find the optimal value of MAX Player from the given graph.
### Steps:
1. Start the program
2. Initially  assign MAX and MIN value as 1000 and -1000.
3.  Define the minimax function  using alpha beta pruning
4.  If maximum depth is reached then return the score value of leaf node. [depth taken as 3]
5.  In Max player turn, assign the alpha value by finding the maximum value by calling the minmax function recursively.
6.  In Min player turn, assign beta value by finding the minimum value by calling the minmax function recursively.
7.  Specify the score value of leaf nodes and Call the minimax function.
8.  Print the best value of Max player.
9.  Stop the program. 

### Program:
<img width="986" height="966" alt="ex 4 pr" src="https://github.com/user-attachments/assets/6b76dff8-cb8b-4d58-8ff2-1d93ec3e6f82" />

### Output:
<img width="1178" height="332" alt="ex 4 o" src="https://github.com/user-attachments/assets/dd55cd79-4e8e-45d5-bca0-2997792ebb60" />

### Result:
Thus the best score of max player was found using Alpha Beta Pruning.
