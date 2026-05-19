# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program and import the required library (numpy).
2. Initialize the matrix for which the LU decomposition needs to be found.
3. Apply LU Decomposition.
4. Display the results.

## Program:
(i) To find the L and U matrix
```Python
from scipy.linalg import lu
import numpy as np
A=np.array(eval(input()),dtype=float)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```Python
from scipy.linalg import lu_factor,lu_solve         
import numpy as np
A=np.array(eval(input()),dtype=float)
B=np.array(eval(input()),dtype=float)
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/87c486f7-fae3-429f-821b-7a47841aa28a" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e64a21c6-425e-4a16-bd86-9f18e5d3cccc" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

