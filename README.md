# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212225040045
# Developed By:Bavin Balaji R
# 1-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:Bavin Balaji R
RegisterNumber: 212225040045
'''


# Type your code here
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array (eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np

mat = np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
<img width="1459" height="806" alt="image" src="https://github.com/user-attachments/assets/39a8b273-dfc7-42ed-b4c4-058d4fe31b6c" />

<img width="1521" height="858" alt="image" src="https://github.com/user-attachments/assets/7aa7f026-b881-467a-8bf8-50798d820d3b" />

<img width="1436" height="818" alt="image" src="https://github.com/user-attachments/assets/d4b8d3f3-3842-4001-aae2-57838d4c486a" />
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
