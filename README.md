# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy as any variable
### Step 2: let assume any variable
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print eigen values and eigen vectors

## Program:
```
## Program:#Program to find the eigen values and eigen vectors.
#Developed by: VASANTH P
#RegisterNumber:212222240113
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/Vasanthpushpa/EIGENVALUES-AND-EIGENVECTORS/assets/119291100/c4a9dc76-d274-42d5-8203-a6bdf0df35e3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
