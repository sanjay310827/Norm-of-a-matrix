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

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input())) 
ans=np.linalg.norm(mat,2)
N="{:.2f}".format(ans)
print(N)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))  
ans=np.linalg.norm(mat,np.inf)
N="{:.2f}".format(ans)
print(N)

```
## Output:
### 1-Norm of a Matrix
<img width="527" height="146" alt="image" src="https://github.com/user-attachments/assets/52be0ac1-6154-4441-a635-ee6186e413a1" />


### 2-Norm of a Matrix
<img width="461" height="204" alt="image" src="https://github.com/user-attachments/assets/dabf216f-acec-429f-a942-0f1fb9d27b3f" />


### Infinity Norm of a Matrix
<img width="509" height="167" alt="image" src="https://github.com/user-attachments/assets/7fc8ee12-dfbb-44e2-b99a-80ac9b372855" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
