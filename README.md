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
# Register No: 212225220003
# Developed By: ADHI SELVAKUMAR R
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=eval(input())
one_mat=np.linalg.norm(mat,1)
print("{:.2f}".format(one_ma


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
mat=eval(input())
two_mat=np.linalg.norm(mat,2)
print("{:.2f}".format(two_mat))


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=eval(input())
m=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(m))






```
## Output:
### 1-Norm of a Matrix
<img width="790" height="377" alt="Screenshot 2026-06-03 085839" src="https://github.com/user-attachments/assets/ce0fe66c-8a02-4676-8198-5b949f406c5c" />
<img width="681" height="340" alt="Screenshot 2026-06-03 085848" src="https://github.com/user-attachments/assets/bcd3b7cf-e20e-403e-8c95-3ad79c0e2109" />


### 2-Norm of a Matrix
<img width="640" height="418" alt="Screenshot 2026-06-03 085854" src="https://github.com/user-attachments/assets/80ac40dc-b163-41b8-aa9b-3688f63f710f" />
<img width="770" height="403" alt="Screenshot 2026-06-03 085859" src="https://github.com/user-attachments/assets/62467d12-7a79-4b9a-9321-b76c8df4e8be" />


### Infinity Norm of a Matrix
<img width="755" height="420" alt="Screenshot 2026-06-03 085905" src="https://github.com/user-attachments/assets/8d15514d-d0f6-4d33-86ab-c8100dfc41e6" />
<img width="800" height="390" alt="Screenshot 2026-06-03 085910" src="https://github.com/user-attachments/assets/63cf6f59-5f59-45d7-a1f7-e3f8999f43a1" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
