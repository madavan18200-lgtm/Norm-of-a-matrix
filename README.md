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


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





# Infinity Norm of a Matrix





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="527" height="182" alt="image" src="https://github.com/user-attachments/assets/41db59d7-5f67-4be5-ad29-f84c3df8e090" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="545" height="207" alt="image" src="https://github.com/user-attachments/assets/ef6483c6-69f6-4a92-ad63-aa823631ebdd" />


### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="617" height="217" alt="image" src="https://github.com/user-attachments/assets/0d060ad9-d536-492b-84eb-6f79b14e2346" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
