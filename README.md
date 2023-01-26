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
def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1
    for i in range(1,smaller):
     if(n1%i==0 and n2%i==0):
         gcd=i
    print("GCD of two numbers is:",gcd)
```
/*
Program to find the gcd of two number using function.
Developed by: 
RegisterNumber:  
*/
```

## Output:
![image](https://user-images.githubusercontent.com/121215786/214828498-08db2ee6-c09f-4e4f-8402-6cfa2a48c836.png)





## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
