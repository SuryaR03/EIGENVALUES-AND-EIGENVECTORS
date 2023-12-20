# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### step1:
Import the numpy module to use the built-in functions for calculations
### Step 2: 
Prepare the list from each eigenvalues,eigenvectors and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: SURYA R
#RegisterNumber:23013019
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
## Output:
![Screenshot 2023-12-20 104153](https://github.com/SuryaR03/EIGENVALUES-AND-EIGENVECTORS/assets/147140237/0b1fd6c3-3435-4118-b609-8cb388a5ab7a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
