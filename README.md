# N-QueenJSGA
A Genetic Algorithm implemented to solve the N-Queen Problem, which is a very popular combinatorial optimization problem.

# N-Queen
The N Queen is the problem of placing N chess queens on an N×N chessboard so that no two queens attack each other. For example, following is a solution for 4 Queen problem. The expected output is a binary matrix which has 1s for the blocks where queens are placed.
[Reference](https://www.geeksforgeeks.org/n-queen-problem-backtracking-3/).

## GA's Characteristics
 + Solution is represented as a permutation vector with "n" integers, where n is the number of queens to be placed;
 + Partially Mapped Crossover (PMX);
 + Swap mutation;
 + Parents selection based on a tournament between *k* individuals;
 + Merging populations based on total ranking;
 
## Parameters
The page presents some parameters through which one may notices their impact in the algorithm behavior. Such parameters and their default values are:  
 - *Population size:* **100** 
 - *Mutation rate:* **0.05**
 - *Crossover rate:* **0.80**
 - *Maximal of generations:* **200**
 - *K-tournament:* **3**
 - *N-Queens:* *8*

#### External libs
  - [jQuery](http://jquery.com) - Help js codification
  - [Bootstrap](https://getbootstrap.com) - Deal with front page appearance
  
  Remember we are talking about a pure JavaScript toy running in your web browser. It is regarding to didactic material with no intention to be performatic.
