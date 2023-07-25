# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
create a function called as circulate
### Step 2:
get input from the user as a list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the list
### Step 6: 
end the program
## Program:
```
#Program to circulate N values.
#Developed by: THAANESH.V
#RegisterNumber:23003843
def circulate():
    num1=eval(input())
    num2=int(input())
    result=num1[num2:]+num1[:num2]
    print("After circulating the values are:",result)
```
## Output:
![output](/Screenshot%202023-07-25%20134636.png)
## Result:
```
The Program executes successfully
```