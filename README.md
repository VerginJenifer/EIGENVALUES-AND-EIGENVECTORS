# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for
calculation
### Step 2: 
Prepare the lists from each linear equations and assign in
np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: D Vergin Jenifer
#RegisterNumber: 23004210
import numpy as np
eigenvalues, eigenvector=np.linalg.eig([[-2,2,-3],[2,1,-6],[-1,-2,0]])
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvector)
```
## Output:
![image](https://github.com/VerginJenifer/EIGENVALUES-AND-EIGENVECTORS/assets/136251012/b9a5cfae-e931-4c07-9b0e-101a8f471570)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
