# DATE:
# EX-05 LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy extension and scipy.linalg extension
2. Initialize the matix values
3. Use lu functions from imported extensions
4.  Print the output

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: DEEPIKA R 
RegisterNumber: 212223230038
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
## Output:
![image](https://github.com/user-attachments/assets/ebe2b2a5-d35e-4d9f-b254-9c72aa8677f9)

(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: DEEPIKA R 
RegisterNumber: 212223230038
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
![image](https://github.com/user-attachments/assets/3c4d5b8b-7408-4e79-92af-21f317ca96e8)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

