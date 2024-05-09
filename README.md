# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MOHAMED HAMEEM SAJITH J
#RegisterNumber:212223240090
import numpy as np
matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
![image](https://github.com/Sajith7862/EIGENVALUES-AND-EIGENVECTORS/assets/145972360/386f351b-399f-44a1-96b8-e9cc2e6280ba)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
