# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### program (i)
### Step 1: Define the package as scipy.linalg import lu.
### Step 2: Get input from user and print L and U matrix by 'print' .
### Step 3: Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
### Step 4: print the variable 'X' 

### program (ii)
### Step 1: Import the required libraries (numpy, scipy.linalg.lu_factor, lu_solve)
### Step 2: Get coefficient matrix A input from the user
### Step 3: Get constant matrix B input from the user
### Step 4: Perform LU decomposition on matrix A using lu_factor()

## Program:
(i) To find the L and U matrix
```python
#Program to find the L and U matrix.
#Developed by: Kamlesh.Y
#RegisterNumber: 212224100029
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
#Program to find the LU Decomposition of a matrix.
#Developed by: Kamlesh.Y
#RegisterNumber: 212224100029
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
(i) To find the L and U matrix

![image](https://github.com/user-attachments/assets/412a3ae3-9d04-4297-ba15-d8a373f10e29)

(ii) To find the LU Decomposition of a matrix

![image](https://github.com/user-attachments/assets/152edc0b-8846-4c18-b5ed-32fcf013d4b2)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

