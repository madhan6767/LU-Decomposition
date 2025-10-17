# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy library
2. create the nesscary matrices by .array() methods
3. and using respective functions to calculate the answers
4. displaying the output using print

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
<img width="1219" height="432" alt="image" src="https://github.com/user-attachments/assets/bd8aa2b7-28c3-4c84-be31-bdf32c6ef29f" />


<img width="1016" height="244" alt="image" src="https://github.com/user-attachments/assets/eab2b7f5-8a95-4ced-9b17-75615364af56" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

