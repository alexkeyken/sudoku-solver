### PROJECT UNDER CONSTRUCTION ###
### SUDOKU IMAGE SOLVER ###

A simple Python sudoku solver that combines filling singletons (cells where only one digit is allowed) with recursive backtracking guesses.
The board and box sizes are set by constants, so it can handle layouts other than the standard 9x9, such as 6x6 boards with 2x3 boxes.

- To do list:

1. Train CNN to recognise typed digits in images.
2. Add image processing to recognise sudoku boards in images, then pass the digits to the CNN.
3. Add board check before solving algorithm to reject impossible puzzles immediately.
4. Add limitations and update readme with usage instructions...
