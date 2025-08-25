# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: S Sanjay
#RegisterNumber: 212224110047
#include <stdio.h>


import numpy as np


A = np.array([[1, -3],   
              [3,  1]])  


B = np.array([0, 10])


solution = np.linalg.solve(A, B)

print(solution)
```


## Output:
<img width="1351" height="572" alt="image" src="https://github.com/user-attachments/assets/3be2737f-9e67-46ac-aa3e-cbecf4b3d26c" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

