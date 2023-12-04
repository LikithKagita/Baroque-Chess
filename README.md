# Baroque-Chess
Ai | Python
# baroque chess

This is a collaborative project between me and another student.  We developed a bot for playing Baroque Chess, which is basically Chess with a great deal crazier portions and regulations.(general rules can be seen on [Wikipedia](https://en.wikipedia.org/wiki/Baroque_chess)).  

# baroque chess vs regular chess:

The king is the one piece alone that is limited to moving exactly one square at a time.
All of the remaining pieces on the first rank may move like the queen, in all directions.
The pawns, on the other hand, move just like the rook moves in chess, unable to move diagonally

# command for demo:

python BaroqueGameMaster.py PlayerSkeletonA PlayerSkeletonB 5

# command explanation:

python BaroqueGameMaster.py <player1_module> <player2_module> <time_limit>

# final command:

python3 BaroqueGameMaster.py terminator_BC_Player terminator_BC_Player 5

# algorithms used:

The main code for the bot is in terminator_BC_Player.py, which uses the minimax search algorithm with alpha-beta pruning for finding the most optimal move given a board state. Zobrist hashing is also implemented, which helped reduce the search time by at least 30%.
#implementation 
-visual studio code(vs code) or pycharm 
#execution 
-windows powershell or cmd(command prompt)

Note: Run the code with different time limits to get different outputs
