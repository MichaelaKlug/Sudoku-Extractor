
# Sudoku Extractor

### Done by: Michaela Klug, Tristen Haverly

## Description

This Python code is designed to help solve Sudoku puzzles using computer
vision techniques and a Convolutional Neural Network (CNN) model for
digit recognition to convert the image of a Sudoku puzzle into text with
can then be passed into a Sudoku solver. The code takes an input image
of a Sudoku puzzle, performs various image processing steps to extract
the grid and individual cells, and then uses the trained CNN model to
recognize the digits in each cell. Finally, the code outputs the Sudoku
puzzle from the image as a text-based grid.

## Structure

-   `src.ipynb` is the script
-   `Images` contains sample images
-   `Sqaures` will contain the images of the sqaures to be passed into
    the digit recognition model

## Prerequisites

Before running the code, make sure you have the following dependencies
installed:

OpenCV (cv2) NumPy (numpy) scikit-image (skimage) matplotlib
(matplotlib) scipy (scipy) TensorFlow (tensorflow)

You can install these dependencies using the following command in your
console:

#### pip install opencv-python numpy scikit-image matplotlib scipy tensorflow

## How to run

#### Follow these steps to run the Sudoku solver:

Perform the following steps:

-   navigate to the directory with the `src.ipynb` script and
    excecute the script
-   make sure your images folder is saved in the correct directory

## Output

The Sudoku solver provides the following output:

The Sudoku grid will be printed on the console. If the image processing
fails or the digits cannot be recognized accurately, an error message
will be displayed. The intermediate steps of image processing, including
grid extraction and digit recognition, will be shown in the console for
debugging purposes. Please note that the accuracy of the digit
recognition model may affect the correctness of the solved Sudoku
puzzle.
