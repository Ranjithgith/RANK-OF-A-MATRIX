# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step 1: Import the required library numpy as np.
Step 2: Define the matrix as a 2D NumPy array with the given elements.
Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
Step 4: Print the rank of the matrix.
```
## Program:
```
#Program to find the rank of a matrix.
#Developed by:RANJITH KUMAR R 
#RegisterNumber:212224240131
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

# Given matrix
A = np.array([[5, -3, -10],
              [2,  2,  -3],
              [-3, -1,  5]])

# Find rank
rank = np.linalg.matrix_rank(A)

# Print result
print(rank)
```
## Output:

<img width="1351" height="867" alt="Screenshot 2026-05-05 112328" src="https://github.com/user-attachments/assets/cc403df1-d363-4b95-b1ec-d4c7e76769d8" />



## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

