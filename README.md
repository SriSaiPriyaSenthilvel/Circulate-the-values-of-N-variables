# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: Get the values to be circulated from the user.
### Step 2: Get the value from the user for the number of rotation.
### Step 3: Using the slicing concept rotate the list.
### Step 4: Print the circulated values using print statement.
### Step 5: End the program.
## Program:
```
#Program to circulate N values.
#Developed by: SRI SAI PRIYA.S
#RegisterNumber:22006141
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![output](/Screenshot%20from%202022-12-26%2021-30-15.png)
## Result: Thus program to circulate the N variables using function concept is successfully executed.
