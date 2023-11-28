# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the value from the user for the number of rotation  
### Step 2: 
Get the value from user for list
### Step 3: 
Using the slicing concept to rotate the list

### Step 4: 
print the value of circulated list

## Program:
```
#Program to circulate N values.
#Developed by: LATHIKESHWARAN J
#RegisterNumber:212222230072
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print('After circulating the values are:',l)
```
## Output:
![Screenshot 2023-11-28 175648](https://github.com/LATHIKESHWARAN/Circulate-the-values-of-N-variables/assets/119393556/45fdb71a-8b73-457b-9f08-ea4bab987670)


## Result:
The program to circulate the value of n variables executed successfully
