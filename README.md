# N-Queens Using Deap

The task was to place eight chess queens on the board without any two of them threatening each other. In other words, no two queens can share the same row, same column, or same diagonal. The N-Queens problem is similar, using an N×N chessboard and N chess queens.

Utilizing DEAP, a python framework used for rapid prototyping and testing of ideas, two solutions were found and compared; Position-Index-Based and Row-Index-Based. After finding the best individual it was discovered that the fitness score was 0 in the Row-Index-Based solution. On first attempts at finding the best fitness score a minimum value of 1 was found. After changing the comparison of the elements in the algorithm in the Row-Index-Based solution, a fitness score of 0 was achieved. The more generations with low fitness ratings, the lower the fitness will be until eventually all the fitness scores become 0 entirely.
