# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

1. Import the numpy module to use the built-in functions for calculation

2. From scipy package import lu

3. Get the input from the user and assign in np.array()

4. Find the L and U matrix using lu 

5. Print the L matrix and U matrix 

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by:Sowmya V 
RegisterNumber: 22005551

import numpy as np  #from numpy import array
from scipy.linalg import lu
arr=eval(input())
a=np.array(arr)
P,L,U=lu(a)
print(L)
print(U)

```
## Algorithm:

1. Import the numpy module to use the built-in functions for calculation

2. From scipy package import lu_factor,lu_solve

3. Get the input from the user and assign in np.array()

4. Get the B matrix from the user

5. Find the solution using lu_factor,lu_solve

6. Print the solution.

## Program:
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Sowmya V
RegisterNumber: 22005551


import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
a=np.array(arr)
b=eval(input())
res=lu_factor(a)
sol=lu_solve(res,b)
print(sol)
```

## Output:
![output1](/out1.png)

![output2](/out2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

