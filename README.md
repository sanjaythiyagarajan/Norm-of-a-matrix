# Norm of a matrix

## Aim

To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:

1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
	
## Algorithm:

1.Get the input matrix using np.array()   

2.Find the 2-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.

## Program:
```

# 1-Norm of a Matrix

'''
Program to find 1-Norm of a matrix
Developed by:Sanjay T
register number:212222110039
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: sanjay T
RegisterNumber: 212222110039
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)




# Infinity Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: sanjay T
RegisterNumber: 212222110039
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)



```
## Output:

### 1-Norm of a Matrix

![7a maths](https://github.com/sanjaythiyagarajan/Norm-of-a-matrix/assets/119409242/31ce9a94-1e41-46fc-983a-22067a5d4c3d)

### 2-Norm of a Matrix

![7b maths](https://github.com/sanjaythiyagarajan/Norm-of-a-matrix/assets/119409242/7cd608e0-2828-445d-8df3-5e9e8caab492)

### Infinity Norm of a Matrix

![7c maths](https://github.com/sanjaythiyagarajan/Norm-of-a-matrix/assets/119409242/90c7845d-d4ea-4a79-a37f-b677fd4bdfea)

## Result:

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
