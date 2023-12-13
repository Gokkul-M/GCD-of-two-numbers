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
#program to find the gcd of number using function
#Developed By:Gokkul M
#RegisterNumber: 23014201
def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print(f"GCD of two numbers is: {a}")
```

## Output:
![image](https://github.com/Gokkul-M/GCD-of-two-numbers/assets/144870543/127c5b36-b5ad-4a30-a750-b52f9bc9919f)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
