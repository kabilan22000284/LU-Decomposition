# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy library using import statement.
2.From scipy package import lu().
3.Get input from user and pass it as an array.
4.Get P, L, U matrix using lu()
5.Print L and U matrix

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: kabilan V
RegisterNumber: 212222100018

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: kabilan V
RegisterNumber: 212222100018

import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_solve([LU,P],B)
print(res)
```


## Output:
(i) To find the L and U matrix
![Screenshot (38)](https://github.com/kabilan22000284/LU-Decomposition/assets/123469171/1dd5ef62-43e3-4e92-b89a-6eb87373d9f9)
(ii) To find the LU Decomposition of a matrix 
![Screenshot (39)](https://github.com/kabilan22000284/LU-Decomposition/assets/123469171/8f4b40c8-43ff-48e1-a9e8-d5d33fb39f4d)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

