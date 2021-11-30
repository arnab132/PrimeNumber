# Prime Number Implementation using Python

A positive integer greater than 1 which has no other factors except 1 and the number itself is called a Prime Number.

2, 3, 5, 7 etc. are Prime numbers as they do not have any other factors. But 6 is not prime (it is composite) since, 2 x 3 = 6.

Given two Positive integers start and end. The task is to write a Python program to print all the Prime numbers in an interval.

Definition: A Prime Number is a natural number greater than 1 that has no positive divisors other than 1 and itself. The first few prime numbers are {2, 3, 5, 7, 11, ….}.
The idea to solve this problem is to iterate the Val from start to end using a for loop and for every number, if it is greater than 1, check if it divides n. If we find any other number which divides, print that value.
