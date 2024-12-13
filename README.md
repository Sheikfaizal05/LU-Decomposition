# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## STEP 1: find the l and u matirx by using numpy and linalg from scipy
## STEP 2: print the l matrix and u matirx
## STEP 3: find the lu decomposition by using numpy and lu_factor and lu_solve
## STEP 4: print the the following matrix
## Program:
```
(i) To find the L and U matrix
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
```
/*
Program to find the L and U matrix.
Developed by: SHEIK FAIZAL S
RegisterNumber:24900982
*/
```
```
(ii) To find the LU Decomposition of a matrix
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

```
/*
Program to find the LU Decomposition of a matrix.
Developed by:SHEIK FAIZAL S
RegisterNumber:24900982
*/
```

## Output:
![alt text](image.png)
![alt text](image-1.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

