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
# Register No:23001835
# Developed By:DHANUSH P
# 1-Norm of a Matrix
import numpy as np 
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)

```
## Output:
### 1-Norm of a Matrix
![WhatsApp Image 2023-12-29 at 16 18 52_8b296928](https://github.com/Dhanush0143/Norm-of-a-matrix/assets/139841924/fdf9380f-b020-41a5-8211-68a09842f823)

<br>
<br>
<br>

### 2-Norm of a Matrix
![WhatsApp Image 2023-12-29 at 16 18 52_79002b61](https://github.com/Dhanush0143/Norm-of-a-matrix/assets/139841924/5ee36530-4168-463b-898e-7616298458e2)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![WhatsApp Image 2023-12-29 at 16 18 52_f62b3b56](https://github.com/Dhanush0143/Norm-of-a-matrix/assets/139841924/d3877055-0a47-487f-a2c5-893e48c217d6)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
