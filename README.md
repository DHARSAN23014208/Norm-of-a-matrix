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
```
Program to find 1-norm of a matrix 
Developed by: DHARSANKUMAR R
Register Number:23014208

import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,1)
norm="{:.2f}".format(sol)
print(norm)
```

# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: DHARSAN KUMAR R
RegisterNumber: 23014208

import numpy as np
a=([[1,2],[3,4]])
b=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,2)
norm="{:.2f}".format(sol)
print(norm)

```

# Infinity Norm of a Matrix
```
Program to find 1-norm of a matrix
Program develobed by:DHARSAN KUMAR R
Register number:23014208

import numpy as np
arr=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(sol)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/DHARSAN23014208/Norm-of-a-matrix/assets/149365413/160df567-f51f-4071-b2bd-33eea436559b)


### 2-Norm of a Matrix
![image](https://github.com/DHARSAN23014208/Norm-of-a-matrix/assets/149365413/05a267cf-9836-4e71-aa50-bf74592f1d30)


### Infinity Norm of a Matrix

![image](https://github.com/DHARSAN23014208/Norm-of-a-matrix/assets/149365413/ac1e146f-b28c-4cd8-91ab-e810d5e5a734)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
