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
# Register No:212223100054
# Developed By:Sriharan JV
# 1-Norm of a Matrix
'''
program to find 1-normm of a matrix.
Developed by:Sri haran
Register number:212223100054
'''
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:2f}".format(one_matrix))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Sriharan
RegisterNumber: 212223100054
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix
'''
Program to find infinity-norm of a matrix.
Developed by: Sriharan
RegisterNumber: 212223100054
'''
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/sriharan23000516/Norm-of-a-matrix/assets/139841769/76b199dd-342f-4b56-9845-f5dd52399f1c)

### 2-Norm of a Matrix
![image](https://github.com/sriharan23000516/Norm-of-a-matrix/assets/139841769/e28b8507-12b3-45d8-bdd3-c2f11f413687)


### Infinity Norm of a Matrix
![image](https://github.com/sriharan23000516/Norm-of-a-matrix/assets/139841769/c913cceb-b934-406f-b158-0ec34b11eb1c)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
