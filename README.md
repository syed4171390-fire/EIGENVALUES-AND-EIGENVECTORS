 # EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program

## Program:
```
import numpy
a = numpy.array([[4,2],[2,4]])
b,c = numpy.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c)
```

## Output:
<img width="999" height="673" alt="Screenshot 2026-02-26 203652" src="https://github.com/user-attachments/assets/5e15f516-4a90-47c8-867a-2ab62c5de6ce" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
