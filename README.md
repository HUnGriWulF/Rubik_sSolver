DESCRIPTION OF THE PROJECT

  Hello there , what i have made is a 3x3 standard Rubik's cube solver.
  It allows the user to randomly shuffle a cube in it's solved state as many times as they wish and then gives the steps to solve it.

Concepts Used 

    I have used the concepts of Graph algorithms like BFS, DFS ,IDDFS and IDA*/Korf's algorithm to implement the solver function as well as basic OOPS and virtual function to design a 
    common parent class to derive our functions from it.


Flow of my project can be broadly classified into 3 steps:

  1) Modelling of the cube(How i am representing the current state of my cube , i have made 3 models for the representation , 1D modelling , 3D modelling and Bitboard modelling)
  2) Random shuffling of the cube (For this there are 18 primary moves of the cube and i implemented those moves in derived class after inheriting from parent class and then mapping
         the moves with number from 1 to 18 and randomly generating number from 1 to 18 to shuffle the cube)
  3) Solving the Cube (I experimented with various algorithms to optimise my solve time for the cube , like i used DFS for memory optimisation , BFS for time optimisation , and IDDFS and          and IDA* algorithm which in a way acted as Trade-Off between them
  
 











  
   
