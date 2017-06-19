Matrix Generator
===========
A module that generates or extends a matrix.

Create a module that generates a matrix within the scope of the module. This module should expose three methods. generateMatrix: generates a matrix with the given values, extendMatrix: extends the matrix to a larger size, and getMatrix: returns the matrix in memory.

The generateMatrix method should take in a columns, rows, and fill arguments.

    columns: the number of columns to generate
    rows: the number of rows to generate
    fill: the value to populate each cell of the matrix with

generateMatrix(4, 4, 0);  

| 0 | 0 | 0 | 0 |  
|---|---|---|---|  
| 0 | 0 | 0 | 0 |  
| 0 | 0 | 0 | 0 |  
| 0 | 0 | 0 | 0 |  


The extendsMatrix method will take in the same arguments.

  columns: the new number of columns
  rows: the new number of rows
  fill: the value to populate any new cell in the matrix


extendMatrix(6, 6, 1);  

| 0 | 0 | 0 | 0 | 1 | 1 |  
|---|---|---|---|---|---|  
| 0 | 0 | 0 | 0 | 1 | 1 |  
| 0 | 0 | 0 | 0 | 1 | 1 |  
| 0 | 0 | 0 | 0 | 1 | 1 |  
| 1 | 1 | 1 | 1 | 1 | 1 |  
| 1 | 1 | 1 | 1 | 1 | 1 |  

The getMatrix method should take in no arguments and should return the matrix in its current state.



## Getting Started
1. Clone this repository
2. To retrieve all dependecies, run the command: `npm install`
3. Your work will be done in the file named: `generate_matrix.js`
