# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Define the package as scipy.linalg import lu
2.  Get input from user and print L and U matrix by 'print'. 
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as "X" include the package in that variable. 
4. Print the variable "X".

## Program:
(i) To find the L and U matrix
```
/*
'''
Program to find L and U matrix using LU decomposition.
Developed by: NAVEEN KUMAR M
RegisterNumber: 212222110028
'''
import numpy as np 
from scipy.linalg import lu 
arr=np.array (eval (input () ))
P,L,U=lu(arr)
print(L)
print (U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: NAVEEN KUMAR M
RegisterNumber: 212222110028
'''

# To print X matrix (solution to the equations)

import numpy as np
from scipy. linalg import lu_factor, lu_solve
A=eval (input ())
B=eval (input ())
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print (X)

*/
```

## Output:
![lu decomposition]()
![image](https://github.com/NAVEENMATHIVANAN/LU-Decomposition/assets/119394582/c6804e4f-5834-4282-ac4b-37f3b8067a94)

![image](https://github.com/NAVEENMATHIVANAN/LU-Decomposition/assets/119394582/59f7758f-bdae-4823-8e24-3d2f0fa55337)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

