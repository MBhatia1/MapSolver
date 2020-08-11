# MapSolver

A C++ project for my EECS 281: Data Structures & Algorithms class. The program finds solutions to multi-dimensional puzzle game level maps. Each level consists of the following structures:

 + ".": Floor 
 + "#": Wall 
 + "@": Player 
 + "?": Exit 
 + "[A-Z]": Door 
 + "[a-z]": Button 
 + "^": Spike trap

The objective of the puzzle game is for the player to reach the exit. The player moves one space at a time and may not move diagnoally. Stepping on a button of a certain letter, or "color", will open the corresponding door and close all others. Stepping on a spike trap will reset all doors.

The map solver takes a text file as input. Reads in 3 ints from the first line, representing the number of colors in the level, and the x and y dimensions of the level respectively. Ignores all comments. Underneath, the program reads in a map drawn in ASCII, and will generate the fastest solution (if possible) to the level. The solution is sent to terminal output.

Unfortuantely, due to the honor code at my school, I cannot post this project for the time being. If you are a recruiter and would like to see this project, please contact me at manavb@umich.edu
