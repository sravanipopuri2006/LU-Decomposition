# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np and from scipy.linalg import lu
2. Use np.array() to declear the matrices
3. The function lu() gives L and U matrix and lu_factor() function used to find the lu decomposition of the matrix
4. Print the following L and U matrices and LU decomposition of the matrix

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:popuri sravani
RegisterNumber:23006561
'''

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:popuri sravani
RegisterNumber:23006561 
'''

# To print X matrix (solution to the equations)

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)


```

## Output:

i)
![Alt text](<2023-07-25 (10).png>)

ii)
![Alt text](<2023-07-25 (9).png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

