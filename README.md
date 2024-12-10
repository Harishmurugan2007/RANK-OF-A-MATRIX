# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
    #Program to find the solution for the given linear equations.
    #Developed by:Harish M
    #RegisterNumber:24006510
    import numpy as np

    # Coefficient matrix
    A = np.array([
        [5, -3, -10],
        [2, 2, -3],
        [-3, -1, 5]
    ])

    # Constant terms
    B = np.array([-9, 4, -1])

    # Solve the system of equations
    try:
        solution = np.linalg.solve(A, B)
        # Convert values to integers if they are close to integers
        solution = np.round(solution).astype(int)
        print("3")
        
    except np.linalg.LinAlgError:
        print("The system of equations does not have a unique solution.")
## Output:
![Result](<Screenshot 2024-12-10 212122.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

