# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Importing numpy
### Step 2:
Giving the matrix as array
### Step 3: 
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Printing the answer
## Program:
```
# EIGENVALUES-AND-EIGENVECTORS
#Developed by:S.Devesh sharma
#Reference no: 22005350
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
![image](https://user-images.githubusercontent.com/121490523/215414781-7e83efbd-4dd4-49b2-a721-1f3ca7684d23.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
