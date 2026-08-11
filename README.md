# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
# NAME : SHAJIVE KUAMR J
# REG NO : 212225230258
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
Display the values of the unknown variables (solution of the linear equations) and end the program.
End the program
## Program:
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[1, -3],
              [3, 1]])

B = np.array([0, 10])


solution = np.linalg.solve(A, B)

print(solution)
```

## Output:
<img width="1491" height="845" alt="Screenshot 2026-08-11 112126" src="https://github.com/user-attachments/assets/ae3e7aed-b981-484a-b5e9-d9554068e0b6" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

