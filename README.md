# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End of program.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:gokul j 
#RegisterNumber:22009062
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
i=np.linalg.inv(a)
print(i)

```

## Output:
![inv matrix](https://user-images.githubusercontent.com/121165938/212668038-787bea69-2b5d-4cee-936c-8394b2eec228.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

