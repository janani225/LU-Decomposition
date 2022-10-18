# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1.Import the numpy module to use the built-in functions for calculation.

2.From scipy.linalg module import the lu funtion.

3.Get inputs from the user and assign the values in np.array().

4.Using the lu() function,we can find the L and U matrix.

5.Print the obtained values.

6.End the program.

## Program:

(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: V.S.JANANI
RegisterNumber: 22003192 

# To print L and U matrix
import numpy as np
from scipy.linalg import lu
a=eval(input()) 
P,L,U=lu(a) 
print(L)
print(U)
```

##  OUTPUT
![Screenshot from 2022-09-24 13-35-38](https://user-images.githubusercontent.com/113497680/192087625-46068974-7953-4d4a-b93e-0f99cb106113.png)

##  Result:
Thus the program to find the LU decomposition of a matrix is written and verfied using python programming.


## Algorithm:
1.Import the numpy module to use the built-in functions for calculation.

2.From scipy.linalg module import lu_factor and lu_solve functions for calculations.

3.Get inputs from the user and assign the values in A and B in np.array().

4.Using the lu_factor(),we can find the LU and pivot.

5.Substitue the value in a variable obtained from lu_solve().

6.Print the variable.

7.End the program.


## Program

(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: V.S.JANANI
RegisterNumber: 22003192

# To print X matrix (solution to the equations)
import numpy as np
from scipy. linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![Screenshot from 2022-09-24 13-56-21-1](https://user-images.githubusercontent.com/113497680/192088423-7036ad07-00dc-40e0-9af2-ad84a8f32448.png)

## Result:
Thus the program to solve the matrix using LU Decomposition is written and verified using python programming.
