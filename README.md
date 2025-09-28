# 2D Arrays (Multidimensional Arrays) and it's Operations in C++

# Aim : To study and implement operations on 2D arrays (matrices) in C++.

# Tools: VS Code

# Theory:
What is a 2D Array?
A two-dimensional array (2D array) in C++ is a collection of elements stored in rows and columns, like a table or matrix. It is used to represent mathematical matrices or tabular data.It stores data in a grid-like structure, where each element can be accessed by two indices — one for the row and one for the column.

# Key points:
Declared as data_type array_name[rows][columns];

Each element is accessed using array[i][j]

Useful for matrix operations like addition, multiplication, transpose, and diagonal summation.

#  Applications of 2D Arrays :
1. Mathematical Matrices:
Used to store and manipulate matrices in linear algebra.
Enables operations like addition, subtraction, multiplication, transpose, determinant, etc.
2. Tabular Data (Tables & Grids):
Represents data in rows and columns, like a spreadsheet.
3. Image Processing:
A grayscale image can be represented as a 2D array of pixels (integers).
4. Game Development:
Games that use grids (like Tic Tac Toe, Chess, Sudoku, Minesweeper) can use 2D arrays for the game board.
Program Explanations :
1. 2D Array Input and Display:
This program demonstrates how to take input-output in a matrix and display it in matrix form 2D array handling.

# Algorithm:

Initialize a 3×3 integer matrix.

Request user to input all matrix elements.

Read elements using row-wise nested loops.

Assign each value to its corresponding matrix index.

Print the matrix.

# 2. Matrix Addition:
This program adds two matrices of the same dimensions by summing their corresponding elements and stores in other matrix, if dimensons are not same then it will prompt user .

Algorithm:

Accept row and column sizes for two matrices as user input.

Verify matrix dimensions match for addition compatibility.

Declare separate 2D arrays to store both matrices.

Populate matrix elements through row-column iteration.

Print both matrices with proper formatting.

Compute sum by adding corresponding elements position-wise.

Output the resultant matrix

# 3. Matrix Multiplication:
This program multiplies two matrices where columns of matrix 1 match rows of matrix 2 and store it in other matrix if dimensions doesn’t match so it will prompt user.

Algorithm:

Input rows and columns for both matrices.

Check if column count of matrix 1 equals row count of matrix 2.

Input elements of both matrices.

Initialize result matrix to zero.

Multiply for each element of result, sum products of row elements of matrix 1 and column elements of matrix 2.

Display the result matrix.

# 4. Addition of diagonal elements of a 2-D Array:
This program calculates the sum of diagonal elements in a square matrix (same number of rows and columns) if matrix dimensions are not same then it will prompt user about it.

Algorithm:

Input matrix dimensions.

Declare 2D array mat[x][y] and input elements

Display the entered matrix with proper formatting

Check if matrix is square (x == y): If true: Calculate sum of diagonal elements (mat[i][i]) If false: Display "Diagonal sum not possible"

Output the diagonal sum result or error message

# 5. Matrix Transpose:
This program creates the transpose of a matrix by swapping its rows with columns.

Algorithm:

1.Accept row and column dimensions as user input.

Initialize original and transposed matrix structures.

Populate matrix elements through row-wise nested iteration.

Print the input matrix with proper formatting.

Generate transpose by interchanging indices (mat_T[j][i] = mat[i][j]).

Output the transposed matrix with flipped dimensions.

# 6. Comparing Two Matrices:
This program checks if two matrices are exactly equal in both size and element values, if not user will be prompted appropriately.

Algorithm:

Input dimensions of both matrices.

If dimensions are unequal, report not equal.

Input elements of both matrices.

Loop through all positions in both matrices:

If any mismatch is found, mark as not equal and exit loop.

Print result accordingly.

# Conclusion:
In this experiment, We performed matrix input, display, addition, multiplication, diagonal sum, transpose, and row comparison using nested loops and 2D arrays. This helped us understand how to use two-dimensional arrays effectively for mathematical and data-based operations. We also learned the logic behind row-column traversal, element-wise operations, and condition checking in matrices. The experiment enhanced our logical thinking and improved our C++ programming skills for real-life matrix problems.
