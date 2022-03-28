# sudoku_solver

Different methods for solving sudokus are implemented in this project.
In the first notebook of the project (sudoku_solver.ipynb) I implemented both human rules and computer algorithms to solve sudokus.

My next step is to build and train and OCR model to be able to recognize the numeric array from a picture and solve the sudoku.
I am currently working on that, there are several steps inside it:

* First is to be able to recognize the main square grid of a sudoku and the location of the numbers of blank spaces on it.
* Then is to recognize the number at every cell and get a numeric array representing the sudoku.
* After that, algorithm to solve the sudoku can be implemented

Next objetive can be to create an image of the solved sudoku adding the new numbers to the first image's white cells.

Last update (28/03/2022): I uploaded the Image_preprocessing notebook where, using mainly OpenCV functions, the main square sudoku grid is recognized and cropped. Then the single cell images are splitted. From there a Convolutional Neural Network can be trained to recognize the different digits.
