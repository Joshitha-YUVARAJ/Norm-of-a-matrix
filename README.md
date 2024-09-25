## DATE:
## EX-7 Norm of a matrix
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
# Register No:212223240189
# Developed By:YUVARAJ JOSHITHA
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/4e23bbe2-47f1-4983-ad3b-ef7e6a08ecc6)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/fdb093ad-56fc-4f42-ab0a-42099daa3442)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/9e4afe72-5deb-4469-a5f0-990854b62045)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
