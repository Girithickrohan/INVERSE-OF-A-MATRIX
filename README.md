# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Check if the matrix is square
### Step 2: Check if the matrix is singular (non-invertible)
### Step 3: Use Gauss-Jordan elimination to find the inverse
### Step 4: Extract the inverse matrix from the augmented matrix

## Program:
```
import numpy as np
matrix=np.array([[2,1,1], [1,1,1], [1,-1,2]])
inverse_matrix=np.linalg.inv(matrix)
print(inverse_matrix)
```
## Output:
![image](https://raw.githubusercontent.com/Girithickrohan/INVERSE-OF-A-MATRIX/main/Screenshot%202023-11-29%20133028.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

