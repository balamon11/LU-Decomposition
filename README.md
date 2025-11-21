# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: BALAJI T 
RegisterNumber: 25005672
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
X,L,U=lu(A)
print(L)
print(U)


*/
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: BALAJI T
RegisterNumber: 25005672
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
A,B=lu_factor(a)
X=lu_solve((A,B),b)
print(X)
*\
```
## Output:
<img width="1456" height="812" alt="Screenshot 2025-11-21 225449" src="https://github.com/user-attachments/assets/e508f7d6-4e77-4b2c-a055-b846aa6692a7" />

<img width="1595" height="929" alt="Screenshot 2025-11-21 225427" src="https://github.com/user-attachments/assets/0b415ad2-4708-446f-8252-21ee1496796b" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

