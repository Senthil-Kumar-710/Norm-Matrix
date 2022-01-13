# 2-Norm of a matrix
## Aim
To write a program to find the 2-norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()
	2. The 2-Norm of a matrix is given by 
![norm](./normeqn1.jpg)
    
    3. Find the 2-norm of the matrix using np.linalg.norm()
	4. Print the norm of the matrix in two decimal places.
## Program:
```
'''
Program to find 2-norm of a matrix.
Developed by: Senthil Kumar S
RegisterNumber: 21500410
'''
import numpy as np
n=eval(input())
value=np.linalg.norm(n,2)
print("{:.2f}".format(value))





```
## Sample Input and Output:
![norm1](./input.jpg)

## Output



![Capture](https://user-images.githubusercontent.com/93860256/149291816-94f6097e-ca46-40a4-850a-7db6e6e37c8e.PNG)




## Result
Thus the program for 2-norm of a matrix is written and verified.
