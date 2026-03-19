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
#Program to find the solution for the given linear equations.
#Developed by:  VIJAYARAGHAVAN
#RegisterNumber: 212225100058
import numpy as np

A=[[1,-3],[3,1]]

B=np.array([0,10])

C=np.linalg.solve(A,B)

print(C)

## Output:<img width="1291" height="718" alt="Screenshot 2026-03-19 105921" src="https://github.com/user-attachments/assets/1c19060b-e79a-4da4-8aef-cba52e692850" />



## Result: 
Thus the solutions for the linear equations are successfully solved using python program

