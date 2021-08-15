# 8-queens-genetic-algorithm
Very fast problem solving of 8 queens with genetic algorithm.

### How to try?
1. Clone this repository: [8-queens-genetic-algorithm](https://github.com/alirezaeftekhari/8-queens-genetic-algorithm)
1. Run main.py: ```python3 main.py```
1. Enter the number of solutions you want

After these steps, your output should look like the following:
![output image in console](https://github.com/alirezaeftekhari/8-queens-genetic-algorithm/blob/readme/output.png?raw=true)

### Why does this algorithm work faster than other algorithms?
The main difference between this algorithm and other algorithms is that before the children are produced by the parents, first the parents' heuristic is calculated based on the position of the queen and then, As much as possible, the queen's position on the chessboard changes to reach a fitness level of 28, otherwise the parents will have children.
