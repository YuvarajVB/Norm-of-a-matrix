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
# Register No: 23013769
# Developed By: Yuvaraj V
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr = np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-25 062355](https://github.com/YuvarajVB/Norm-of-a-matrix/assets/151488375/62964251-764d-4dc1-a0ec-8f4b43cb0433)
### 2-Norm of a Matrix
![Screenshot 2023-12-25 062409](https://github.com/YuvarajVB/Norm-of-a-matrix/assets/151488375/705973e7-cd9a-4662-8f36-2682959e4ba9)
### Infinity Norm of a Matrix
![Screenshot 2023-12-25 062451](https://github.com/YuvarajVB/Norm-of-a-matrix/assets/151488375/86457b49-d70e-40e1-9571-50dbcc167355)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
