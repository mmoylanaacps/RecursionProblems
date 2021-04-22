Complete at least 4 of the recusive functions in main.py

Given n of 1 or more, return the factorial of n, which is n * (n-1) * (n-2) ... 1. Compute the result recursively (without loops).

Ex:
 factorial(1) → 1
 factorial(2) → 2
 factorial(3) → 6

```
def factorial(n):
  
```

We have a number of bunnies and each bunny has two big floppy ears. We want to compute the total number of ears across all the bunnies recursively (without loops or multiplication).

Ex:
bunnyEars(0) → 0
bunnyEars(1) → 2
bunnyEars(2) → 4

```
def bunnyEars(n):
  
```

The fibonacci sequence is a famous bit of mathematics, and it happens to have a recursive definition. The first two values in the sequence are 0 and 1 (essentially 2 base cases). Each subsequent value is the sum of the previous two values, so the whole sequence is: 0, 1, 1, 2, 3, 5, 8, 13, 21 and so on. Define a recursive fibonacci(n) method that returns the nth fibonacci number, with n=0 representing the start of the sequence.

Ex:
fibonacci(0) → 0
fibonacci(1) → 1
fibonacci(2) → 1

```
def fibonacci(n):
  
```

We have people standing in a line, numbered 1, 2, ... The odd people (1, 3, ..) get 2 slices of pizza. The even people (2, 4, ..) get 3 slices of pizza. Recursively return the number of slices needed for lines of different sizes line 1, 2, ... n (without loops or multiplication).

Ex:
pizzaSlices(0) → 0
pizzaSlices(1) → 2
pizzaSlices(2) → 5

```
def pizzaSlices(n):
  
```

Given a non-negative int n, return the sum of its digits recursively (no loops). Note that mod (%) by 10 yields the rightmost digit (126 % 10 is 6), while divide (//) by 10 removes the rightmost digit (126 // 10 is 12).

Ex:
sumDigits(126) → 9
sumDigits(49) → 13
sumDigits(12) → 3

```
def sumDigits(n):
  
```

Given a non-negative int n, return the count of the occurrences of x as a digit, so for example if n is 717 and num is 7 it yields 2. (no loops). Note that mod (%) by 10 yields the rightmost digit (126 % 10 is 6), while divide (//) by 10 removes the rightmost digit (126 // 10 is 12).

Ex: 
#countNum(717,7) → 2
#countNum(2,2) → 1
#countNum(123,5) → 0
```
def countNum(n,x):
  
```