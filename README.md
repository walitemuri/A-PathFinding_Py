## A* Pathfinding Visualisation

## Description

This is an implementation of the A* pathfinding function using the PyGame library in Python. The heuristic function uses the manhattan distance from the starting node and end node in order to calculate the h-cost. 

## Running

```zsh
python App.py
```

## Functionality

When the app is running the first click on the grid will be marked as the start node and the spot clicked next is determined as the end node. Every subsequently clicked spot on the grid will be marked as a wall node and the algorithm will not consider them as potential moves.


https://user-images.githubusercontent.com/108627530/216388410-bc17be3e-8dbd-486c-904f-cf872622c46d.mov

Pressing the C key will clear the entire grid.




https://user-images.githubusercontent.com/108627530/216388656-4997dcc1-fb7b-4a49-b76f-72d342601259.mov


After setting up the board as you wish, press the space key in order to start the pathfinding visualisation app. Here is an example run:


https://user-images.githubusercontent.com/108627530/216388859-ebd1cfa2-6687-4404-81df-d2d6c5d10b7c.mov



