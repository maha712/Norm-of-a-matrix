# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

1. Get the input matrix using np.array()   

2. Find the 2-norm of the matrix using np.linalg.norm()

3. Print the norm of the matrix in two decimal places.

## Program:

# Register No:212222240057

# Developed By:mahalakshmi.k

# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)

# 2-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)


## Output:

### 1-Norm of a Matrix

![Screenshot (18)](https://github.com/maha712/Norm-of-a-matrix/assets/121156360/a18cd9ed-846f-4941-bdfe-579b57dbf7e3)


### 2-Norm of a Matrix

![Screenshot (20)](https://github.com/maha712/Norm-of-a-matrix/assets/121156360/d5e99589-9ed9-41d3-aef7-48af1141d4b5)


### Infinity Norm of a Matrix

![Screenshot (21)](https://github.com/maha712/Norm-of-a-matrix/assets/121156360/261e41dc-0825-4e3b-87a9-8c6225f139c6)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
