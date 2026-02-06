# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:

```
#Program to find the inverse of a matrix.
#Developed by: SARVESH.M
#RegisterNumber:212225240140

import numpy as np

A = np.array([
    [6, 2, 3],
    [3, 1, 1],
    [10, 3, 4]
    ])
A_inv = np.linalg.inv(A)
print(A_inv)

```

## Output:

<img width="1884" height="911" alt="Screenshot 2026-02-06 084822" src="https://github.com/user-attachments/assets/e15cb666-91ca-4ac4-aa40-241b1f74fe30" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

