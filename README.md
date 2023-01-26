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
# 1-Norm of a Matrix
```
#Python program to find the 1-Norm of a matrix and display the results in two decimal places.
#Developed by: PRADEEP.S
#RegisterNumber: 22009034

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: PRADEEP.S
RegisterNumber:22009034

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```
Program to find the infinity of a matrix and display the result in two decimal places.
Developed by: PRADEEP.S
RegisterNumber:22009034

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![7a1](https://user-images.githubusercontent.com/120539823/214775689-ab826eeb-9195-4627-842d-16074818aa28.png)


### 2-Norm of a Matrix
![7a2](https://user-images.githubusercontent.com/120539823/214775709-5e2a7e4c-5b6c-4847-bbd9-81ab8ea82d0f.png)


### Infinity Norm of a Matrix
 ![7a3](https://user-images.githubusercontent.com/120539823/214775736-4135faf4-7c40-40d7-ae99-661209a732eb.png)

 
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
