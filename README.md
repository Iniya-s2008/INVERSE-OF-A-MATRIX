# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.inv(), we can find the rank of the given matrix.
### Step 4: print and stop the program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Iniya S
#RegisterNumber:212225230104
import os 
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
matrixA=np.array([[2,1,1],[1,1,1],[1,-1,2]])
res=np.linalg.inv(matrixA)
print(res)
```
## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/efb26e12-ad1f-4d40-b055-43160be4ea53" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8a2d97e3-77c7-4831-b371-006b4f0b9f12" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

