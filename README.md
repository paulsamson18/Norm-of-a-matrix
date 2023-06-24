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
# Register No:212222230104
# Developed By: paulsamson s
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)



# Infinity Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm=("{:.2f}".format(ans))
print(norm)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/paulsamson18/Norm-of-a-matrix/assets/119405794/2bed7a24-c0b8-4d52-a38a-c40796562ac2)


### 2-Norm of a Matrix
![image](https://github.com/paulsamson18/Norm-of-a-matrix/assets/119405794/f7ce2674-5fe2-4203-b730-ff26810a1d7b)


### Infinity Norm of a Matrix
![image](https://github.com/paulsamson18/Norm-of-a-matrix/assets/119405794/76a82ae6-4cb5-43bb-8dde-7305b751af91)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
