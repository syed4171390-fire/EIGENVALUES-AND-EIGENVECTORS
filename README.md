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
![image](https://neighbouring-red-uetnz3katk.edgeone.app/Screenshot%202026-03-14%20110635.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
