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
/*
#Program to find L and U matrix using LU decomposition.
#Developed by: ARUNACHALAM M
#RegisterNumber: 212225230019
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
#Program to solve a matrix using LU decomposition.
#Developed by: ARUNACHALAM M
#RegisterNumber: 212225230019
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A =np.array(eval(input()))
B=np.array(eval(input()))
lu, pivot=lu_factor(A)
x=lu_solve((lu, pivot), B)
print (x)
```

## Output:

<img width="552" height="329" alt="Screenshot 2026-05-24 113425" src="https://github.com/user-attachments/assets/fdadbcb9-959a-4e69-8ccd-3abcbf619934" />
<img width="264" height="161" alt="Screenshot 2026-05-24 113457" src="https://github.com/user-attachments/assets/dc35a1f6-077c-4d18-abc1-7462fe62502d" />







## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

