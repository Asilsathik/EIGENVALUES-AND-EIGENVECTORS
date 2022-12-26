# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
mport the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the result and solve the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: mohamedasil
#RegisterNumber:22008522
import numpy as np
A=np.array([[4,2],[2,4]])
value,vector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(value,vector))
```
## Output:
![output](eigenvaluesandvectors.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
