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
# Register No: 22001315
# Developed By: Koti Sai Sankar
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Screenshot from 2023-01-25 23-32-16](https://user-images.githubusercontent.com/118344248/214645552-121ac220-3d87-48c4-99e4-d4c663cb0d34.png)



### 2-Norm of a Matrix
![Screenshot from 2023-01-25 23-33-14](https://user-images.githubusercontent.com/118344248/214645744-bebc1e17-25f1-4f95-bc1c-ec588b6c91cb.png)


### Infinity Norm of a Matrix
![Screenshot from 2023-01-25 23-33-52](https://user-images.githubusercontent.com/118344248/214645829-177bf646-1961-4d0d-ab1f-d9bb771e44a9.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
