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
# Register No: 212223230027
# Developed By: Balamurgan
# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
one=np.linalg.norm(matrix,1)
print("{:.2f}".format(one))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Bala murugan S
RegisterNumber: 212223230027
'''
import numpy as np
matrix=eval(input())
one=np.linalg.norm(matrix,2)
print("{:.2f}".format(one))

# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/bala23005271/Norm-of-a-matrix/assets/155039753/fa1aac32-67f2-4836-83a9-02e790c0ec45)

### 2-Norm of a Matrix
![image](https://github.com/bala23005271/Norm-of-a-matrix/assets/155039753/014e897d-1dc5-4b37-9755-89b012d4038a)


### Infinity Norm of a Matrix
![image](https://github.com/bala23005271/Norm-of-a-matrix/assets/155039753/32e1b350-a71e-4339-906b-5e5561ec22fc)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
