# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :import the numpy module to use the builtin function for calculation 
### Step 2: prepare the lists fromm each linear equation and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:end the changes 

## Program:
~~~python 
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
~~~

## Output:
![eigen](https://user-images.githubusercontent.com/93978702/155523141-6314a37d-4ee1-4094-8f55-b5bc1e4de966.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
