# sudoku_solver

Different methods for solving sudokus are implemented in this project.
In the first and only notebook for now (sudoku_solver.ipynb) I implemented both human rules and computer algorithms to solve sudokus.

My next step is to build and train and OCR model to be able to recognize the numeric array from a picture and solve the sudoku.
I am currently working on that, the whole model is going to be compossed of 3 parts:

* First one is trained to recognize single numbers
* Second one is able to read the image and find the rows and columns of the sudoku, 
  giving the first part of the model the single numbers and then, obtaining the 9x9 array.
* The third part is going to solve the sudoku once it has been recognized from the picture.

Other project can be to create an image of the solved sudoku adding the new numbers to the first image's white cells.
