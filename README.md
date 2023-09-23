# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy libary
### Step 2: 
Assign a variable A
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
import numpy as np
a=np.array([[2,2],[1,3]])
values,vector=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vector))
```

## Output:
![image](https://github.com/Udhayasankaran04/EIGENVALUES-AND-EIGENVECTORS/assets/119393933/8506fe1c-5240-468c-a5bd-8c93d15e47fb)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
