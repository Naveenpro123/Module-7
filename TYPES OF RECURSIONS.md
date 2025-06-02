# EX: 7.2 TYPES OF RECURSIONS
- **Name:** Naveen P
- **Registration Number:** 212222050039
### Aim: To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a recursive case in the first line of function for head recursion.

STEP 4: Print the result.

STEP 5: Stop.
### Program:
```
def fun(n):
     if (n >0):
          fun(n - 2)
      print(n-1, end=" ")
x = int(input())
if(x%2==0):
     fun(x)
else:
     fun(x+1)

```
### Output:
![image](https://github.com/user-attachments/assets/c4d6416f-d333-49c1-9dd5-0f774cdabb03)

Result: 

Thus, the given program is implemented and executed successfully.
