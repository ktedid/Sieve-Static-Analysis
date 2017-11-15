# Sieve-Static-Analysis

New Sieve of Eratosthenes program freed of errors using FindBugs program.

CS1632 Exercise 6: Run the FindBugs program on a Sieve of Eratosthenes program, and then fix any issues found by the FindBugs program. This will allow you to see what kinds of bugs a static analysis program can find (and which ones it cannot).

The Sieve of Eratosthenes is an ancient way of finding all prime numbers below a specific value. For details on the algorithm itself, please see https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes.

This program accepts one integer value and will tell you all prime numbers up to and including the passed-in value. However, there are some defects hidden in the code. You are going to use FindBugs to find and fix them.
