# Data-Structures-and-Algorithms

Chapter 1:  Design and Analysis of Algorithms

Chapter 1.4 - The Running Time of a Program
This section points out the general idea that in an algorithm, as the size of an input increases, in most cases, the time it takes to complete the algorithm also increases.
The section defines a few terms to help to understand this concept:
Time Complexity - the amount of time it takes to run an algorithm.
Big O Notation - a mathematical notation to describes how quickly the time runtime of an algorithm increases.
Constant Time - irregardless of the size of an input, the time the algorithm takes remains the same.
Linear Time - as the size of input increases, the time the algorithm takes increases linearly.
Quadratic Time - as the size of input increases, the time the algorithm takes increases quadratically. 
To change an expression to Big O Notation: Remove the coefficient of the fastest growing term.
Examples: T - time, n - size of input, a and b - constants
T = a = O(1)
T = an + b = O(n)
T = an^2 + bn + c = O(n^2)
The time it takes to run an algorithm is inconsistent throughout computer platforms and computer languages. Big O Notation describes the runtime of an algorithm. Unlike the measurement of time, Big O is consistent since the runtime of an algorithm will always scale in the same manner, regardless of a computer platform, computer speed, or computer language.


