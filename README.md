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
# Register No:
# Developed By:
# 1-Norm of a Matrix
##Program to find the 1-norm of a matrix
#Developed by:John Paul J
#Register no:212223230093
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:John Paul J
RegisterNumber: 212223230093
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:John Paul J
RegisterNumber: 212223230093
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>![output1](https://github.com/JOHNSUBIK/Norm-of-a-matrix/assets/150279319/0b889daf-fa36-4825-a6e4-37158d58105b)

<br>
<br>

### 2-Norm of a Matrix
<br>![output2](https://github.com/JOHNSUBIK/Norm-of-a-matrix/assets/150279319/98336925-5d2d-4da5-bba7-6b78e5930d72)

<br>
<br>

### Infinity Norm of a Matrix
<br>![output3](https://github.com/JOHNSUBIK/Norm-of-a-matrix/assets/150279319/2f0a8260-259e-43ad-8b36-f02ea2fc981a)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
