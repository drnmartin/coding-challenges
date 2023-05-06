# HackerRank Easy Challenges in Python

These are my answers for the challenges on Python.

## Challenge 1: Say "Hello World!" with Python

Print Hello World.

```
my_string = "Hello, World!"
print(my_string)
```

## Challenge 2: Arithmetic Operators

1. The first line contains the sum of the two numbers.

2. The second line contains the difference of the two numbers (first - second).

3. The third line contains the product of the two numbers.

```
print(a + b)
print(a - b)
print(a * b)
```

## Challenge 3: Python Division

The first line should contain the result of integer division, //. 

The second line should contain the result of float division, /. 

```
print(a // b)
print(a / b)
```

## Challenge 4: Python If-Else

Given an integer, perform the following conditional actions:

If is odd, print Weird

If is even and in the inclusive range of to, print Not Weird

If is even and in the inclusive range of to, print Weird

If is even and greater than , print Not Weird

```
if n % 2 != 0:
    print("Weird")

elif n % 2 == 0 and 2 >= n <= 5:
    print("Not Weird")
        
elif n % 2 == 0 and 6 >= n <= 20:
    print("Weird")
        
elif n % 2 == 0 and n > 20:
    print("Not Weird")
```
