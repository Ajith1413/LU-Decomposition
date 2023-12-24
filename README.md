# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step:1.
  Import numpy as np
## Step:2.
  Import library called 'scipy' to solve the lu decomposition.
## Step:3.
   Import lu_factor and lu_solve libraries.
## Step:4. 
 Get the input to solve the lu decomposition.
## Step:5.
 Print the result obtained.
 
## Program:
(i) To find the L and U matrix.
```
/*
Program to find the L and U matrix.
'''Program to find L and U matrix using LU decomposition.
Developed by: AJITH KUMAR A
RegisterNumber: 23002150
'''
import numpy as np
from scipy.linalg import lu

A=np.array(eval(input()))
P,L,U= lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
'''Program to solve a matrix using LU decomposition.
Developed by: AJITH KUMAR A
RegisterNumber: 23002150
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
*/
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/Ajith1413/LU-Decomposition/assets/139842524/50392d14-caac-4168-a912-82c4ba4c94c0)
(ii) To find the LU Decomposition of a matrix
![image](https://github.com/Ajith1413/LU-Decomposition/assets/139842524/e3b39447-d6df-4b00-90d5-1de0af3acb63)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

