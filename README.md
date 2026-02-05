# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : write a python program for the given matrix
### Step 2: import numpy library
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: run the code and get the output

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
## Output:
<img width="1919" height="1199" alt="Screenshot 2026-02-05 140944" src="https://github.com/user-attachments/assets/c00d79b2-6397-45e1-bfc6-de10968f848c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
