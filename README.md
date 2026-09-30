# FizzBuzz in Python

This repository contains a Python implemenation of the FizzBuzz programming challenge.

## About FizzBuzz

The FizzBuzz challenge is a common exercise that is used to demonstrate Python concepts such as conditional Statements, loops and the modulo operator.

+ The program would check numbers from 1 to 100
+ If the number is divisible by 3, it will print `fizz`
+ If the number is divisible by 5, it will print `buzz`
+ If the number is divisible bu both 3 and 5, it will print `fizzbuzz`
+ Otherwise it will just print a number

## FizzBuzz Syntax

```python
for i in range(1, 16):
    if i % 15 == 0:
        print("FizzBuzz")
    elif i % 3 == 0:
        print("Fizz")
    elif i % 5 == 0:
        print("Buzz")
    else:
        print(i)
```

## FizzBuzz Output

```text
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```
## What This Taught Me

By doing this FizzBuzz project it has helped me practice and understand how to use Python loops, conditional statements and the modulo operator. 
