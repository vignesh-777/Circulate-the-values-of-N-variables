# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
start the program
### Step 2: 
get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
using concatenation operation display the entire rotated list
### Step 6: 
stop the program
## Program:
```
#Program to circulate N values.
#Developed by: R vignesh
#RegisterNumber: 23005542
def circulate():
    lst1=eval(input())
    n=int(input())
    lst2=lst1[n:]+lst1[:n]
    print("After circulating the values are:",lst2)
    
```

## Output:

![output](/output.png)

## Result:
Thus the python program for circulate the values of n variables is executed successfully