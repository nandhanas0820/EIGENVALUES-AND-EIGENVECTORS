# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
### #Program to find the eigen values and eigen vectors.
### #Developed by: Nandhana S 
### #RegisterNumber:26011506
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### a=np.array([[2,2],[1,3]])
### values,Vectors=np.linalg.eig(a)
### print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))
## Output:
<img width="1322" height="853" alt="Screenshot 2026-10-13 211448" src="https://github.com/user-attachments/assets/f2296d76-a150-4c8a-ad5f-479fe502262a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
