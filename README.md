# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the list with the given values and assign in np.array()
### Step 3: 
Using np.linalg.inv() we can find the inverse of the matrix
### Step 4: 
End of the program
## Program:
```p
import numpy as np
arr=[[1,0,3],[-1,2,-2],[2,3,-1]]
mat=np.array(arr)
sol=np.linalg.inv(mat)
print(sol)
```
## Output:

<img width="1294" height="804" alt="image" src="https://github.com/user-attachments/assets/24cd4d7d-a2a5-4966-8a05-52111c49b4ee" />

<img width="1291" height="829" alt="image" src="https://github.com/user-attachments/assets/377980dd-b340-4d09-90ea-52585d265dc1" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

