# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
In first step,we import Numpy library and alias it as 'np'.
### Step 2: 
we define 3x3 matrix 'a' using a nested list.
### Step 3: 
we use the np.linalg.inv function to calculate the inverse of a matrix'a'.Store the result in a variable 'b'.
### Step 4: 
We print the inverse matrix 'b' to the console.
### Step 5 :
End the program.

## Program:
````
#Program to find the inverse of a matrix.
#Developed by: SARWESHVARAN A
#RegisterNumber:212223230198

import numpy as np
matrix=np.array([[1,0,3], [-1,2,-2],[2,3,-1]])
result=np.linalg.inv(matrix)
print(result)
````
## Output:

![Screenshot 2024-04-15 203821](https://github.com/Prakash-Chandran/INVERSE-OF-A-MATRIX/assets/147120899/6ca8578d-a48d-4cfc-8093-6dd542356e43)


## Result:
Thus the inverse of given matrix is successfully solved using python program.

