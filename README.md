# Spiral-Primes
Problem Statement
You are tasked with investigating the diagonal elements of square spirals and the ratio of prime numbers among them. A square spiral is constructed by starting with the number 1 in the center and spiraling outwards in an anticlockwise direction.

Square Spiral Construction:

The first square spiral (side length 1) contains just the number 1.
The next layer adds numbers in a square formation, expanding the spiral. For example:
A side length of 3 forms a spiral with the numbers:
7  8  9
6  1  2
5  4  3
A side length of 5 adds more numbers, and so forth.
Diagonals:

The numbers along the diagonals of the spiral can be computed for any given side length. The primary focus is on the two diagonals:
From the top left to the bottom right.
From the top right to the bottom left.
Prime Ratio:

The ratio of prime numbers to total numbers on both diagonals is calculated.
You are to determine the smallest side length 
𝑛
n such that this ratio falls below a specified threshold 
𝑝
p.
Input Format
An integer 
𝑝
p (0 < p < 1), representing the prime ratio threshold.
Output Format
An integer representing the side length of the square spiral for which the ratio of primes along both diagonals first falls below 
𝑝
p.
Example
If the input is 0.2, your program should output the smallest side length 
𝑛
n where the ratio of primes along the diagonals is less than 0.2.
Constraints
The process continues until the side length reaches at least 3 (as the first complete layer must be of side length 3).
