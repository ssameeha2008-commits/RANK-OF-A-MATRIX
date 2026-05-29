# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: SAMEEHA S
#RegisterNumber:212225230243
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixa=([[3,2,5],[1,1,2],[3,3,6]])
result=np.linalg.matrix_rank(matrixa)
print(result)
```
## Output:
<img width="1278" height="281" alt="image" src="https://github.com/user-attachments/assets/317b2d36-c7dd-47bb-861f-b59a4cd38106" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

