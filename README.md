# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step1:
Define a function.
### Step2:
Assign number_iters = 100 in the function to perform 100 iteratios.
### Step3:
Set i = 0.
### Step4:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
### Step5:
Return number

## Program:
```
#Program to find the square root for the given number
#Developed by : DHANDEESWARANSELVAKUMAR
#Register number: 23006838
def newton_method(number,number_iters =100):
        a=float(number)
        for i in range(number_iters):
            number =0.5*(number + a/ number)
        return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:
![square root](https://github.com/dhandeeswaran2005/Square-root-of-a-number/assets/147139188/32b9748e-a431-48fc-9075-9a1af0388eef)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
