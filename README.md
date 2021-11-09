# HackinScienceChallenge
https://www.hackinscience.org/ A compilation of solutions 

8/11/2021 1. First Function
#Function should be named circle_perimeter(radius), where the radius parameter is the radius of a cirle

from math import pi

def circle_perimeter(radius):
    perimeter = radius * pi * 2
    return perimeter

2. Printing even numbers

def print_even_numbers(start, stop):
    for i in range(start, stop):
        if (i%2 ==0):
            print (i)

3. Sum of even numbers <=100
def sum_even():
    total = 0
    for i in range(1, 101):
        if i % 2 == 0:
            total = total + i
    print(total)

sum_even()
