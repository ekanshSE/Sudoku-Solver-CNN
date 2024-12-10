# Sudoku-Solver-CNN

A Python-based Sudoku solver that uses a Convolutional Neural Network (CNN) to recognize and solve Sudoku puzzles from images. This project combines computer vision and deep learning techniques for a complete end-to-end solution.

# Features
Image Processing: Detect and extract Sudoku grids from images.

Digit Recognition: Classify digits using a trained CNN model.

Puzzle Solver: Solve the extracted Sudoku puzzle using a backtracking algorithm.

User-Friendly: Input Sudoku puzzles as images and get solutions in real-time.

# How It Works
Preprocessing:
The input image is processed to detect the Sudoku grid and segment individual cells.
Digit Recognition:
Each cell is passed through a CNN trained on handwritten digits (e.g., MNIST dataset) to identify the numbers.
Solving:
The recognized digits are used to create the Sudoku puzzle, which is solved using a backtracking algorithm.
Output:
The solved Sudoku puzzle is displayed in text format and overlaid on the original image.

# Dataset
The CNN is trained on the MNIST dataset for digit recognition.
Optionally, additional Sudoku-specific datasets can be used to improve accuracy.

# Contributing
Contributions are welcome! Feel free to fork this repository, improve the code, and submit a pull request.
