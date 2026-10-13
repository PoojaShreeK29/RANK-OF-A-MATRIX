# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Read the input.
### Step 2: 
Import the NumPy library as np .
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
Display the rank of the matrix.  
## Program:
###
#Program to find the rank of a matrix.
###
#Developed by:POOJA SHREE K 
###
#RegisterNumber:26018233
###
import os
###
os.environ["OPENBLAS_NUM_THREADS"]="1"
###
import numpy as np
###
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
###
B=np.linalg.matrix_rank(A)
###
print(B)
## Output:
<img width="1000" height="723" alt="image" src="https://github.com/user-attachments/assets/154aaafd-2708-493b-bbc5-f16b143a36d3" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

