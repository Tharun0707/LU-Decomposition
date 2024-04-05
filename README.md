# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy module.
2. Find L and U matrix.
3. Import lu module from scipy.linalg
4. Print the LU matrix.

## Program:
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: Tharun Sridhar
RegisterNumber: 212223230230
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U =lu(A)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
'''Program to solve a matrix using LU decomposition.
Developed by: Tharun Sridhar
RegisterNumber: 212223230230
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu
A=np.array([[3,2,7],
            [2,3,1],
            [3,4,1]])
P,L,U=lu(A)
B=np.array([4,5,7])
x=np.linalg.solve(A,B)
print(x)

## Output:
![image](https://github.com/Tharun0707/LU-Decomposition/assets/145548496/2eaa9734-e440-42d8-a88d-43e6f3968506)
![image](https://github.com/Tharun0707/LU-Decomposition/assets/145548496/5e5694a6-2936-46f4-811d-a8439705232f)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

