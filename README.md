# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:

# Program to find the square root for the given number(newton's method) using function.
# Developed by: ARUNMOZHI VARMAN T
# RegisterNumber:  23002304
```
n=int(input())
a=0.5*n
b=0.5*(a+n/a)
while b!=a:
    a=b
    b=0.5*(a+n/a)
print("Square root of the number:",a)
```


## Output:
![Screenshot 2023-12-21 231822](https://github.com/ArunmozhiVarmanT/Square-root-of-a-number/assets/144870523/3e741e0e-85d2-4259-ae88-42990ba4d5de)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
