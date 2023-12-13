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
'''Program to find L and U matrix using LU decomposition.
Developed by: Nijeesh NJ
RegisterNumber: 23010565 
'''
import pprint
import scipy
import scipy.linalg

a=eval(input())
P,L,U=scipy.linalg.lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
a=eval(input())
b=eval(input())
print(np.linalg.solve(a,b))
```

## Output:
#### 1st Program
<img width="667" alt="image" src="https://github.com/Nijeesh-bit/LU-Decomposition/assets/89188014/90a1fe65-457c-411a-b936-9952f42786bb"> 

#### 2nd Program
<img width="668" alt="image" src="https://github.com/Nijeesh-bit/LU-Decomposition/assets/89188014/64607261-91ec-41a8-8104-1c03af82f20a">



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

