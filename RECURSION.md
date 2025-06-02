# EX: 7.1 RECURSION
- **Name:** Naveen P
- **Registration Number:** 212222050039
### Aim: To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case for termination of the function. STEP 4: Create a recursive case to calculate the result.

STEP 5: Print the result. STEP 6: Stop.

### Program:
```
def sum_digit(n):
       if n<=0:
            return 0
       else:
            return n%10+sum_digit(n//10)
n = int(input())
sum = sum_digit(n)
print(sum)
```
### Output:
![image](https://github.com/user-attachments/assets/50acc657-266e-46e6-ab17-10358494e26c)

### Result: Thus, the given program is implemented and executed successfully .
