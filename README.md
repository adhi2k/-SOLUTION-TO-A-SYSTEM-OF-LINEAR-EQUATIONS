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
#Program to find the solution in the given linear equation
#Program developed by: Adhithya K
#REference number: 2305002001

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
le=np.linalg.solve(a,b)
print(le)

```
## Output
![image](https://github.com/adhi2k/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145216997/a0dd0b33-43a9-4a78-b229-0afa6f2b1ee5)





## Result: 
Thus the solutions for the linear equations are successfully solved using python program

