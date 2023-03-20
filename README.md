# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy folder as np
### Step 2: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 3:
print the values of eigen values and eigen vectors.
### Step 4: 
execute the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Safeeq Fazil.A
#RegisterNumber:212222240086
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evalues,evector))
```
## Output:
![exp4](https://user-images.githubusercontent.com/118680361/226305046-e451080e-a9ee-4139-ac0e-42fce7228292.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
