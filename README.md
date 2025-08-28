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
Program to find the L and U matrix.
Developed by: Vinolia Alaina .R
RegisterNumber: 212224240184
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Vinolia Alaina .R
RegisterNumber: 212224240184
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```

## Output:
(i) To find the L and U matrix
<img width="1213" height="962" alt="Screenshot 2025-08-28 093839" src="https://github.com/user-attachments/assets/7f9438f2-875f-452a-957c-a861b9e3598e" />

(ii) To find the LU Decomposition of a matrix
<img width="1170" height="935" alt="Screenshot 2025-08-28 093851" src="https://github.com/user-attachments/assets/65d63ee9-9ad5-44e5-8b03-de6a731bfd21" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

