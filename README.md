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
Developed by: SWETHA S V
RegisterNumber: 212224230285
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SWETHA S V
RegisterNumber: 212224230285
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![lu decomposition]()
![Screenshot 2025-04-15 103835](https://github.com/user-attachments/assets/653b8cb1-98fa-4959-9af3-1385bfdbbad6)
![Screenshot 2025-04-15 103854](https://github.com/user-attachments/assets/c36dad6d-732b-415c-8a94-4d66587b5336)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

