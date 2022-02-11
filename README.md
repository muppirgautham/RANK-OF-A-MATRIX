# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import numpy library using import statement.
### Step 2: 
Using np.array(), create an array for the given matrix.
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Print the result and end the program.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: GAUTHAM M G
#RegisterNumber:21000182
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
val=np.linalg.matrix_rank(A)
print(val)
```
## Output:
![image](https://user-images.githubusercontent.com/94810884/153621162-c6db59a8-ab96-438d-88bf-4cd594c1cff2.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

