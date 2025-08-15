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
#name:Jayaharshini.s
#register no:212224100024
import numpy as np

A = [[1, -3],
     [3,  1]]

B = [0, 10]

solution = np.linalg.solve(A, B)

print(solution)


# Output:
#<img width="1640" height="942" alt="Screenshot 2025-08-15 073739" src="https://github.com/user-attachments/assets/488527a8-7d64-4031-9a08-81c0f2e78861" />
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

