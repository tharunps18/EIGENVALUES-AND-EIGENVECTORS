# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:  
Import the necessary library, `numpy`, for matrix operations.  

### Step 2:  
Define the given matrix using the `numpy.array()` method.  

### Step 3:  
Using the `np.linalg.eig()`, we get two results (first is eigenvalue and second is eigenvector) of the given matrix.  

### Step 4:  
Display the eigenvalues and eigenvectors using the `print()` function. 

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: THARUN P S
#RegisterNumber: 212224110055

import numpy as np
a = np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:
![image](https://github.com/user-attachments/assets/626c85f1-48c4-4a8a-a0dd-22fd5c0f90a0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
