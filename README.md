# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
importing numpy 
### Step 2: 
get the values in variable A
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the output
## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: Thilakeshwaran
#RegisterNumber : 23013560
import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![output](/output1d.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
