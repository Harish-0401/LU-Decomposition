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
Developed by: Harish S
RegisterNumber: 25010105 
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print (L)
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
from scipy.linalg import lu_factor , lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)

```

## Output:
<img width="867" height="293" alt="image" src="https://github.com/user-attachments/assets/5e2f9fec-a9ce-48ff-984d-cfc1cac38f08" />

<img width="1081" height="421" alt="image" src="https://github.com/user-attachments/assets/6b2e0506-de5e-46d6-af2a-8a0f4e5d9c2d" />

<img width="1047" height="472" alt="image" src="https://github.com/user-attachments/assets/e005a646-5ddb-4b46-953e-1ee4ac7b66ac" />

<img width="905" height="259" alt="image" src="https://github.com/user-attachments/assets/9b912c63-61de-4587-9b88-ac545c94c803" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

