# SolveSudoku
This project extracts and solve sudoku from image. It uses a collection of basic image processing techniques and CNN for training and recognition of characters.
CNN is trained on MNIST dataset.

## Procedure
 > 1. Image preprocessing (Thresholding).
 > 2. Find the largest contour (sudoku square).
 > 3. Get the cordinates of **largest contour**.
 > 4. Crop the image.
 > 5. Perform **Warp perspective** on image
 > 5. Extract each cells from the image by slicing the sudoku grid.
 > 6. Extract the **largest component** in the sudoku image (number).
 > 7. Remove noise in block.
 > 8. Send the number to pre trained Digit Recogition model.
 > 9. Send the grid to Sudoku Solver to perform the final step.

