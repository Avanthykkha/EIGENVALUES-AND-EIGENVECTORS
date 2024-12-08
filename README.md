# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module as np from python library
### Step 2: Define the matrix as "a" using np.array([[],[],[]]).
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Displaying the Eigenvalues and Eigenvectors using print function.


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values, vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot 2024-12-02 105301](https://github.com/user-attachments/assets/237e4ba1-b219-4327-8a42-ef81ca4ed70b)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
