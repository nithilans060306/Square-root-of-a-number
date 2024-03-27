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
```python
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Nithilan S
RegisterNumber: 212223240108
*/
def sqrt(n):
    x = n
    for i in range(100):
        n = 0.5 * (n + (x/n))
    return n
    
n = float(input())
print(f"Square root of the number: {sqrt(n)}")
```

## Output:

![image](https://github.com/nithilans060306/Square-root-of-a-number/assets/147473026/d6870708-803d-4aa0-877c-1e15ae759ab8)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
