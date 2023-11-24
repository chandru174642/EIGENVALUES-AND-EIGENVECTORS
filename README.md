# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built in function for calculation .
### Step 2: 
Prepare the lists from each equation and assigsn in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the Program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:CHANDRU P
#RegisterNumber:23007250
import numpy as np 
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![Screenshot 2023-11-24 133018](https://github.com/chandru174642/EIGENVALUES-AND-EIGENVECTORS/assets/139841798/63ea2ab9-04b4-40f0-875a-28bac3020283)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
