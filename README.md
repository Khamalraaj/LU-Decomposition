# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. from scipy package import lu
3. Get input from the user
4. Print the result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Khamalraaj.S
RegisterNumber: 212224230122
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: khamalraaj.S
RegisterNumber: 212224230122
'''

import numpy as np
from scipy.linalg import lu_factor , lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2025-04-12 132847](https://github.com/user-attachments/assets/7f5dc58e-8f1d-4f5c-aeb7-95d9cd15f885)
![Screenshot 2025-04-12 132856](https://github.com/user-attachments/assets/0f09b6d6-7370-4ed2-8eb6-d5d6fa8423c4)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

