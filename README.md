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
![WhatsApp Image 2024-05-28 at 1 36 48 PM](https://github.com/vasanth0228/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155505264/896d7c99-6891-4aef-a777-c6b22f5e955f)



## Result: 
Thus the solutions for the linear equations are successfully solved using python program
