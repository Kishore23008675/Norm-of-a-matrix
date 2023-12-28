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
# 1-Norm of a Matrix
Program to find 1-norm of a matrix.
Developed by:Ashwath M
RegisterNumber:212223230023 

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))


# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: Kishore A
RegisterNumber: 23008675

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix
Program to find the infinity of a matrix.
Developed by: Kishore A
RegisterNumber: 23008675

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![IMG_5440 (1)](https://github.com/Kishore23008675/Norm-of-a-matrix/assets/144979375/cbe98e08-fac4-4fdf-93a2-1b2d64ae3b25)


### 2-Norm of a Matrix
![out2](https://github.com/Kishore23008675/Norm-of-a-matrix/assets/144979375/8ea05b9a-d272-487b-952c-d4e8b79b27af)


### Infinity Norm of a Matrix
![out3](https://github.com/Kishore23008675/Norm-of-a-matrix/assets/144979375/f6178615-a883-4a6b-87e0-82c3f503abd0)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
