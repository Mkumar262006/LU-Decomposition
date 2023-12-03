# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: MANOJ KUMAR S 
#RegisterNumber: 23002959
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: MANOJ KUMAR S 
#RegisterNumber: 23002959

from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:
![lu_1](https://github.com/Mkumar262006/LU-Decomposition/assets/147139472/05b0bed0-5e64-48a6-90db-76e824e41c8f)
![lu_2](https://github.com/Mkumar262006/LU-Decomposition/assets/147139472/eb533d46-81a5-48e6-9634-10706962047e)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

