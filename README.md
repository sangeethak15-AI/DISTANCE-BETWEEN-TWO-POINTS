# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import numpy module to use built-in functions
### Step 2: 
Get lists from the linear equations and assign it to np.array
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
Print the output
### Step 5: 
End the program
### PROGRAM:
 ```
#Program to find the distance between two points.
#Developed by: Sangeetha.K
#RegisterNumber:21500118
import numpy as np
l1=[10,6]
l2=[4,2]
distance=np.sqrt(((l1[0]-l2[0])**2)+((l1[1]-l2[1])**2)) 
print("{:.2f}".format(distance))
```
### OUTPUT:
![output](./OUTPUT.png)

### RESULT:
Thus the distance between the two points is successfully obtained
