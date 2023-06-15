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
# Developed By: MANOJ G 
# Register No: 212222240060
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
![image](https://github.com/Danielmanoj/Norm-of-a-matrix/assets/69635071/e851f511-e544-4367-a4c2-de568955d14c)

### 2-Norm of a Matrix
![image](https://github.com/Danielmanoj/Norm-of-a-matrix/assets/69635071/d957b68d-79b8-4d91-895a-791bbc2f5e6e)


### Infinity Norm of a Matrix

![image](https://github.com/Danielmanoj/Norm-of-a-matrix/assets/69635071/f96cd728-d2ba-4f82-8e84-482248a1c05a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
