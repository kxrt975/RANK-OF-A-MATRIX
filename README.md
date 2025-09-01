# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Define the matrix 
𝐴
A with given elements.

### Step 2:
Store the elements in a NumPy array for easy matrix operations.

### Step 3:
Use the function np.linalg.matrix_rank(A) to compute the rank of matrix 
𝐴
A.

### Step 4:
Print the rank of the matrix as output
## Program:
```
#Program to find the rank of a matrix.
#Developed by:KARTHIK PADMANABAN R 
#RegisterNumber:212224110029

import numpy as np

A = np.array([[5, -3, -10],
              [2,  2,  -3],
              [-3, -1,  5]])

rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
<img width="1302" height="803" alt="Screenshot 2025-09-01 104058" src="https://github.com/user-attachments/assets/77a781f7-44db-4e21-994f-21c8a44f13f9" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

