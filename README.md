# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Sabeeha Shaik
RegisterNumber: 23012003
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Sabeeha Shaik
RegisterNumber: 23012003
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr = eval(input())
constant = eval(input())
A = np.array(arr)
B = np.array(constant)
result = lu_factor(A)
solution = lu_solve(result,B)
print(solution)
```

## Output:
![image](https://github.com/Sabeeha23/LU-Decomposition/assets/150231876/f2e21598-8f3c-486a-9763-d753b8ac5223)
![image](https://github.com/Sabeeha23/LU-Decomposition/assets/150231876/bbb02f9a-6990-4f02-92c7-df7cfde36fae)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

