# Sudoku.com Solver
### Backtracking Algorithm and Pruning:
The core of the solver is the backtracking algorithm. I implemented a classic backtracking approach to solve the Sudoku. The pruning involves checking the validity of the Sudoku at each step, ensuring the efficiency of the solver. Nothing too fancy.
### Extra Optimizations:
1. **Trivial Moves Optimization:** One of the optimizations included is the step I called "Trivial Moves". This feature allows the solver to iteratively fill cells where only one possible number can go, significantly speeding up the solving process.
2. **Least Possible Options:** Another optimization I introduced is a strategy that starts with the cells having the least possible options. By prioritizing these cells, the solver can make more informed and efficient decisions during the backtracking process, leading to faster puzzle resolution.
### Computer Vision and Image Processing:
I implemented computer vision and image processing techniques to capture the Sudoku puzzle directly from the screen. This way, users can simply display the puzzle on their screen, and the solver will recognize it automatically.
### Machine Learning:
To recognize the digits within the Sudoku puzzle, I employed a simple K-Nearest Neighbors (KNN) model. This model allows the solver to read the digits from the captured image with accuracy.
### GUI Automation:
The project also utilizes GUI automation to interact with the Sudoku.com website. The solver automatically clicks on each cell and inputs the correct digit using the computer vision and machine learning components.
