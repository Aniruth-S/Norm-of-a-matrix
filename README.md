# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

**1. Get the input matrix using np.array()**   
**2. Find the 2-norm of the matrix using np.linalg.norm()** 
 **3. Print the norm of the matrix in two decimal places.**
## Program:
```
# Register No: 212225040020
# Developed By: Aniruth S
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

<img width="898" height="556" alt="{88E29EFE-A11A-47DA-87BA-1291B54FB431}" src="https://github.com/user-attachments/assets/58e25f39-3c86-4f11-a7b2-04bd0e491793" />
<img width="869" height="401" alt="{215F6040-AB3B-4EFE-B78E-F1EEA3788599}" src="https://github.com/user-attachments/assets/2e10649a-7c7d-4b7c-ac15-386f4b303631" />

### 2-Norm of a Matrix

<img width="818" height="664" alt="{25BE094F-A801-4814-9038-24E520E9E641}" src="https://github.com/user-attachments/assets/9952efc4-24d2-4071-9725-3fc7912e9448" />
<img width="857" height="429" alt="{045B82FB-4107-4050-B259-555F145614F3}" src="https://github.com/user-attachments/assets/fc332f03-d295-4c75-8d70-99bd0ffd7da8" />

### Infinity Norm of a Matrix

<img width="861" height="591" alt="{D855674F-DC0D-4C73-B9C4-07858E8F2F46}" src="https://github.com/user-attachments/assets/51758126-dee3-4a07-a3ed-57489ce03511" />
<img width="865" height="410" alt="{9A6E499D-99D6-4C27-8165-3654B86C9A45}" src="https://github.com/user-attachments/assets/3d480a33-4794-477e-b06b-57e4787fd320" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
