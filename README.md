# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Start the program and represent the given equations in matrix form 

### Step 2:
Store the coefficient matrix 
𝐴
A and the constant matrix 
𝐵
B.

### Step 3:
Use the method np.linalg.solve(A, B) to compute the solution of the system.

### Step 4:
Display the solution values of 
𝑥
x and 
𝑦
y.
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by:KARTHIK PADMANABAN R 
#RegisterNumber:212224110029

import numpy as np

A = np.array([[1, 3],
              [2, 5]])

B = np.array([5, -3])

solution = np.linalg.solve(A, B)
print(solution)   # [-34.  13.]
```
## Output:
<img width="1242" height="163" alt="Screenshot 2025-08-20 111827" src="https://github.com/user-attachments/assets/b52769ba-f815-4119-8a58-61ffe8705d8d" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

