# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Firstly, import numpy as np.
### Step 2: 
Next, input the values of the matrix by using np.array([]).
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Finally, print the result value and result vector to display in the output.
### Step 5:
End of the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Hari Prasath. P
#RegisterNumber: 23005079
import numpy as np
a = np.array([[4,2],[2,4]])
value,vector = np.linalg.eig(a)
print("Eigen values are", value, "and Eigen Vectors are", vector)
```
## Output:
![output](/Screenshot%202023-07-29%20121914.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
