# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
import numpy as np
### Step 2:
from scipy package import lu
### Step 3:
get input from the user
### Step 4:
print result

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: NARENDHARAN.M
RegisterNumber: 212223230134
```
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U,=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Aaliya Fathima.M
RegisterNumber: 212223230001
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

```

## Output:

![image]![alt text](<Screenshot 2025-05-28 185356-1.png>)
![image]![alt text](<Screenshot 2025-05-28 185405-1.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

