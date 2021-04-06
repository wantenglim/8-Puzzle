# 8-Puzzle

A 3-by-3 sliding puzzle with 8 square blocks labeled 1 through 8 and an empty space. The number 0 is used to represent the empty space. The Iterative Deepening A Star (IDA*) algorithm is applied to solve 8 Puzzle by achieving the goal state as

![goal state](https://github.com/wantenglim/8-Puzzle/blob/main/Images/Goal%20State.png)

## How To Run:
1. Upload helperfunctions.py to 8Puzzle.ipynb
2. Upload input.txt if desire to take input using txt file
3. Run all the code cell in 8Puzzle.ipynb

## Input
There are 3 types of input method to set the initial state.

1. Use input.txt
2. Take user input row wise
3. Use random number

![initial state](https://github.com/wantenglim/8-Puzzle/blob/main/Images/Initial%20State.png)

## Evaluation Function
The final evaluation function is f(n) = g(n) + h(n) where g(n) is the sum of the step costs from the initial state to node n and there are two types of heuristics functions, h(n):

1. H1 - Calculated based on the total number of misplaced tiles (excludes empty tile - 0) at each row and column.

2. H2 - Euclidean Distance Method

## Output
The final output of the program are Moves, Number of Nodes Expanded, Time Taken(ns), Memory Used and Search Tree Images.

![h1 Result](https://github.com/wantenglim/8-Puzzle/blob/main/Images/h1%20Result.png)
![h1 Search Tree Iteration 1](https://github.com/wantenglim/8-Puzzle/blob/main/Search%20Tree%20Images/h1/h1Iteration1.png)

