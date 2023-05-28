# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
Developed by: ARHAM S
RegisterNumber:  212222110005
def gcd():
    if(a>b):
        smaller = b
    else:
        smaller = a
    for i in range (1,smaller+1):
        if(a%i==0 and b%i==0):
            h=i
    print("GCD of two numbers is:",h)
a = int(input())
b = int(input())

```

## Output:
![photo](https://github.com/arhamshajahan/GCD-of-two-numbers/assets/127313881/6738ad31-3c26-482d-b955-cc26541a339d)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
