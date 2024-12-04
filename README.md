
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculations.
### Step 2: Prepare the lists from each equations and assign in np.array().
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End of the program.

## Program:
```
import numpy as np
a= np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```


## Output:

![Screenshot (2006)](https://github.com/user-attachments/assets/8396ce64-1978-4a2a-b467-e7682d29473e)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
