# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. TO FIND L AND U MATRICES WITH LU DECOMPOSTION
step 1:
Get the matrix from user

step 2: 
Using "from scipy.linalg import lu"to import scipy (lu)

step 3:
print the result matrices (l and u matrices)

step 4:
End the program

2. TO FIND X MATRIX WITH LU DECOMPOSITION
step 1:
Get the matrix from user

step 2:
Using "from scipy.linalg import lu_factor,lu_solve"to import
scipy module for factorization

step 3:
Using "lu,piv=lu_factor(a)"print the matrix

step 4:
End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: s.thirisha
RegisterNumber: 22001920
import numpy as np          #from numpy import array
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:s.thirisha 
RegisterNumber: 22001920
# To print X matrix (solution to the equations)
import numpy as np          #from numpy import array
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

*/
```

## Output:
![Screenshot_20230121_194647](https://user-images.githubusercontent.com/120380280/213871547-5ee947e2-f566-439b-8770-3029d32f5ead.png)

![Screenshot_20230121_194743](https://user-images.githubusercontent.com/120380280/213871552-359c9eaf-fb76-4cc0-a7d5-df5f452913df.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

