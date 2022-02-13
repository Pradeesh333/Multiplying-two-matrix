# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.
## ALGORITHM:

### Step 1:
Import Numpy as np.
### Step 2:
Get input from the user.
### Step 3:
Create empty lists l1 and l2.
### Step 4:
Use for loop to append the values into the list created.
### Step 5:
Print the product of two arrays.
## PROGRAM: 
```
#To write a python program for multiplying two matrix.
#Developed by: Pradeesh S
#Register Number: 212221240038
import numpy as np
n=int(input())
l1,l2=[],[]
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
a=np.array(l1)
b=np.array(l2)
mul=a*b
print('Product of two arrays is:',mul)
```
## OUTPUT:
![](out.jpg)
## RESULT:
Thus the program is written to multiply two matrix.
