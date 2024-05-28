# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: VASANTH KUMAR V
#RegisterNumber: 2305002027
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
le=np.linalg.solve(A,B)
print('The solution for the given matrix is',le)
```

## Output:
![Screenshot 2024-05-28 133525](https://github.com/vasanth0228/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155505264/9ebab86f-a754-4cd5-98be-ed7ce5e4e061)



## Result: 
Thus the solutions for the linear equations are successfully solved using python program
