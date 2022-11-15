# Maze Solver
The following project is a maze solver where a user clicks a particular path block in the maze and he gets the path to it from the start.
## Implementation in Project
This project supports two functions:

## Creating the GUI: 

* Creating a pre-defined matrix for the maze using combination of 0,1,2 and 9 where-
    0 represent the travelling path or white space.
    1 represent the wall or black space.
    2 represent visited blocks.
    9 represent the target where we have to reach.
    
* JFrame - this class is a type of container which inherits the java.awt.Frame class. JFrame works like the main window where components like labels, buttons, textfields are added to create a GUI.

* Paint function - this function is called in the backend automatically when th JFrame is initialized we are writing this function to print our maze in our GUI. 

## Finding the path via DFS: 

* In this project I basically used a DFS graph approach to reach our required tile position. Other techniques can also be used to get to the desired spot which I will be exploring in further project.

## Result:

* We are able to reach to our desired tile position as represnted by the green path.

![Screenshot (7)](https://user-images.githubusercontent.com/88935131/201938335-79ec23f8-dc0b-45bc-a9d1-398ff9c0c550.jpg)
