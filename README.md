# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step 1: Import the numpy module to use the built-in functions for calculation
Step 2: Prepare the lists from each linear equations and assign in np.array()
Step 3: Using the np.linalg.solve(), we can find the solutions.
Step 4: End the program
```

## Program:
```
#Developed by: M.Mahalakshmi
#RegisterNumber: 212224230148
```
```
import numpy as np
matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```

## Output:

![Screenshot 2025-03-03 084816](https://github.com/user-attachments/assets/a7a6a844-bff5-444c-afa1-15ce74eb4378)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
