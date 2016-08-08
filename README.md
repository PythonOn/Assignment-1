# Assignment-1

## Notes 

Python input() returns the string you've typed on Keyboard

```
name = input("What's your name? ")
```

User Types : John


Now, name becomes equal to "John"

```
a = input("Enter value of a ?")   # Suppose user types 2
b = input("Enter value of b ?")   # Supoose user types 3

sum = a + b # Sum will be "23" and not 5 because input function returns String
```

So we use something called typecasting to convert one data type into other.

```
a = input("Enter value of a ?")   # Suppose user types 2, a is now a string "2"
b = input("Enter value of b ?")   # Supoose user types 3, b is now  a string "3"

a = int(a) # int() converts string to int
b = int(b) 

sum = a + b # Sum will be 5 

#You can also do

a = float(a)  # a becomes 2.0
b = float(b)  # b becomes 3.0

```

## Questions

The formula for computing the final amount if one is earning compound interest is given on Wikipedia as

```
A = P * ( (1 + r/n) ^ (n*t)) 


^ Power is calculated using ** in Python, 5 ** 2 = 25

P is the principal sum
r is the nominal interest rate
n is the compounding frequency
t is the overall length of time the interest is applied (usually expressed in years).
```
1. Write a Python program that assigns the principal amount of 10000 to variable P, assign to n the value 12, and assign to r the interest rate of 8% (0.08). Then have the program prompt the user (take input from the user) for the number of years, t, that the money will be compounded for. Calculate and print the final amount after t years.

2. Write a program that will compute the area of a rectangle. Prompt the user to enter the width and height of the rectangle. Print a nice message with the answer.

3. Write a program with a function that will convert degrees celsius to degrees fahrenheit and takes degree celsius as a parameter and returns the fahreinheit value.
