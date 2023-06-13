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
# Register No:212222230033
# Developed By:S.Dinesh
# 1-Norm of a Matrix
 
Program to find the 1-Norm of a matrix 
Developed by:S.Dinesh
Register Number:212222230033
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))



# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by:S.Dinesh
Register Number:212222230033
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
Program to find infinity of a matrix.
Developed by:S.Dinesh
Register Number:212222230033
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Dineshsekhar2004/Norm-of-a-matrix/assets/119405916/39addadc-545e-4f55-8512-066d664f0b05)

### 2-Norm of a Matrix
![Screenshot (74)](https://github.com/Dineshsekhar2004/Norm-of-a-matrix/assets/119405916/2d712076-2b17-4fa2-9ab0-33a1c47e2d94)


### Infinity Norm of a Matrix
![image](https://github.com/Dineshsekhar2004/Norm-of-a-matrix/assets/119405916/53e68caa-9176-4630-adab-ff647ec4e072)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
