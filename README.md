# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Import the NumPy library.
Define the matrix.
Use np.linalg.inv() to calculate the inverse.
Display the original matrix.
Display the inverse matrix.

## Program:

# Program to find the inverse of a matrix
# Using NumPy library

import numpy as np

# Define matrix
A = np.array([[1, 2, 3],
              [0, 1, 4],
              [5, 6, 0]])

# Find inverse
inverse = np.linalg.inv(A)

# Display matrix
print("Matrix:")
print(A)

# Display inverse
print("\nInverse of the matrix:")
print(inverse)

## Output:

Matrix:
[[1 2 3]
 [0 1 4]
 [5 6 0]]

Inverse of the matrix:
[[-24.  18.   5.]
 [ 20. -15.  -4.]
 [ -5.   4.   1.]]

## Result:
Thus the inverse of given matrix is successfully solved using python program

