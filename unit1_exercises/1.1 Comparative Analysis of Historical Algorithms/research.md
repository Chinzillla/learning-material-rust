# Euclid Algorithm

Euclid's Algorithm is an algorithm that is efficient for calculating the greatest common divisor (GCD) of two integers.

Heres an example:

We have two numbers 10 and 30

The greatest common divisor of 10 and 30 is 10, we know this if we divide both 10 and 30 by a number and get an integer, and the highest integer that they are both divisible by is 10.

## Historical Significance

This was the first recorded instance of recursion! Reducing the computation in every step, eventually leading up to a solution.

Using a simple recursive approach to solve complex problems efficienly made it a core algorithmic principle, and made a significat impact on the study of number theory.

## Big O Notation Analysis

- The Time complexity is O(log(min(a,b)))
- The Space complexity is O(1)

Why is time complexity O(log(min(a,b)))?
- https://www.geeksforgeeks.org/time-complexity-of-euclidean-algorithm/

This is much more efficient/simpler than making a full pass to check every single divisor

## Modern Applicability

Today Euclidean Algorithm Applies to, but not limited to

Cryptography
- RSA encryption algorithms that rely on number theory. RSA algorithm uses Euclidean Algorithm to compute the GCD in the key generation phase to make sure the selection of proper coprime numbers

Coding Theory
- Error detection and correction codes, uses GCD to ensure data integrity. Techniques like Reed-Solomon codes, for CDs, DVDs, and QR codes use Euclids Algorithm to correct errors in data storage and retrieval

Computer graphics and Computational Geometry
- Optimize performance and accuracy for algorithm design

Network Design
- Used to optimize routing protocols and network resource allocation. By calculating GCD, network designers can ensure efficient data packaget distribution and minimize congestion. Also helps Digital signal processing for frequency alanysis and filter design.

# Sieve of Eratosthenes

## Historical Significance

## Big O Notation Analysis

## Modern Applicability