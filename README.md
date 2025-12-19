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
Python
```
# Register No:25016155
# Developed By:A.Aira Dario
```
# 1-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(norm1)
```


# 2-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
norm2=np.linalg.norm(a,2)
print(f"{norm2:.2f}")

```



# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(f"{b:.2f}")





```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1200" alt="Screenshot 2025-12-19 162142" src="https://github.com/user-attachments/assets/03dec133-623f-4372-ad03-21f629017af8" />


### 2-Norm of a Matrix
<img width="1920" height="1200" alt="Screenshot 2025-12-19 162152" src="https://github.com/user-attachments/assets/1441adf9-a27a-4fa7-90dc-7f541d1c284a" />


### Infinity Norm of a Matrix
<img width="1920" height="1200" alt="Screenshot 2025-12-19 162158" src="https://github.com/user-attachments/assets/7590a476-093e-42fd-bc1a-375235b12ccf" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
