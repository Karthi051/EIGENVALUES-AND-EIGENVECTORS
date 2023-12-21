# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: Define the matrix 'a'
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: KARTHI KEYAN K
#RegisterNumber:23013936
import numpy as np
A=[[4,2],[2,4]]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/ArchanaSharikalHarinarayanan/EIGENVALUES-AND-EIGENVECTORS/assets/148327224/7b6b364e-25be-462f-88dd-f095dec480fa)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
