# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import math library using import statement
### Step 2: 
Define the two points into two separate lists
### Step 3: 
Substitute the values in the distance formula  ![formula](/.formula.jpg)
### Step 4: 
Print the final value rounded upto two decimals using format function. It would display the distance value
### Step 5: 
end the program
### PROGRAM:
```
  #Program to find the distance between two points.
#Developed by:logeshwari
#RegisterNumber:21500746
import math
l1=[10,6]
l2=[4,2]
value=math.sqrt(((l1[0]-l2[0])**2)+((l1[1]-l2[1])**2))
print("{:.2f}".format(value))
```

### OUTPUT:
![output](./EX03OUTPUT.png)


### RESULT:
Thus the python program to find the distance two points is successfully executed.
