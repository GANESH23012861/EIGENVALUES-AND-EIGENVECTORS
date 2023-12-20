# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program.
### Step 2: 
Import numpy which is an built-in function and get the list values.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Selvaganesh R
#RegisterNumber: 23012861
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are',values,'and Eigen Vectors are',vectors)

```

## Output:
![Screenshot 2023-12-20 122538](https://github.com/GANESH23012861/EIGENVALUES-AND-EIGENVECTORS/assets/147139861/d002cd3f-bdbf-4702-bd90-c4bcb603459d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
