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
# Register No: 212223230048
# Developed By: DILIP MP 
# 1-Norm of a Matrix

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))


# 2-Norm of a Matrix

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix

import numpy as np
matrix=eval(input())
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(infinity_matrix))



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-23 105735](https://github.com/DilipDofy/Norm-of-a-matrix/assets/147223497/ce0a1e38-aeaa-41be-8677-9f64c6585213)

### 2-Norm of a Matrix
![Screenshot 2024-04-23 105838](https://github.com/DilipDofy/Norm-of-a-matrix/assets/147223497/0b82f18b-0b14-4e14-85d9-55da6aa77c74)

### Infinity Norm of a Matrix
![Screenshot 2024-04-23 105932](https://github.com/DilipDofy/Norm-of-a-matrix/assets/147223497/a9b732f0-0daa-4738-bbb5-13b238da42ed)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
