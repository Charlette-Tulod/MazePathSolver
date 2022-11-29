# MazePathSolver

## Option 2

Source Code - https://www.codeproject.com/Articles/9040/Maze-Solver-shortest-path-finder?fbclid=IwAR3ihjz8zZtzVL4P3kGbJEkZUJmXOVlfRN-769bNl9gimCMfQJ1wADT0pWc

By Syed Mehroz Alam

### Modification 
     I modified the maze grid for it to be the same as the grid of our search algorithm activity and midterm.
         - Changed the dimensions into 10x13			
         - Changed the size into 45
         - Add numbers to the grid so we can identify its path
         - Modified the unpassable boxes by having an ‘X’ along side with its number
         - Show the numbers in the path from start state to goal state
         - Changed the colors for the unpassable rectangles, the path, and the starting state
         - Remove diagonal implementation 

### Feature
     Breath first search is used in the source code for its path finder
         - Along side with the breadth first search, Greedy best first search is implemented where a 
           user can select using a radio button which searching algorithm he/she wants to use.
