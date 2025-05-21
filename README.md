# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Get the input matrix using np.array()   
### Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
### Step 3:
Print the norm of the matrix in two decimal places.
### Step 4:
End the program.
## Program:
```Python
# Register No:212224240024
# Developed By:BHARANI KUMAR J
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: BHARANI KUMAR J
RegisterNumber: 212224240024
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: BHARANI KUMAR J
RegisterNumber: 212224240024
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: GAUTHAM KRISHNA S
RegisterNumber: 23012450
'''
import numpy as np
mat = np.array(eval(input()))
norm = np.linalg.norm(mat,ord=np.inf)

print('{:.2f}'.format(norm))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/3cd9458f-cea7-4326-9056-32a40985f40c)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/699c1c6c-3c98-4f03-882f-1faf7b3fb2fd)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/adac2fe0-a154-414c-ac9f-cc48c3d99bf6)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
