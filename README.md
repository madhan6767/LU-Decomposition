# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. importing the numpy library
2. creating matrices using .array() methods
3. peforming calculations
4. showing the answers using print

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
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
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, pivot = lu_factor(A)
x = lu_solve((lu, pivot), B)
print(x)
```

## Output:

<img width="1223" height="471" alt="image" src="https://github.com/user-attachments/assets/c15a2cce-5f24-4cb0-9395-961498e9a682" />

<img width="1073" height="226" alt="image" src="https://github.com/user-attachments/assets/b51640d0-a7ac-4cc5-81c8-bb475d8725b8" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

