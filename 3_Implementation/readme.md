   Implementation of Snake and Ladder
  -----------------------------------------------------------------------------------------------

- The idea is to consider the given snake and ladder board as a directed graph with number of vertices equal to the number of cells in the board. 
- The problem reduces to finding the shortest path in a graph. 
- Every vertex of the graph has an edge to next six vertices if next 6 vertices do not have a snake or ladder.
 
   
    Folder Structure
   ------------------------------------------------------------------
   
    Folder           |            description 
  ------------------ |----------------------------------------------------------
    `inc`            |       All header files  
    `src`            |           Main source code for calculator 
    `test`           |            All source code and data for testing purposes 
    `build`          |            Build output (Not included in git) 
    
