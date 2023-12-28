# Big Integer C++ Library

## Operations:
1. Basic Arithmetic
- Addition(+)
- subtraction(-)
- multiplication(x, lowercase “X”)
- division(/)
2. Exponentiation
- Base will be a big int and exponent will be < 263
3. GCD of two numbers
4. Factorial

## Constraints: 
- For all operations the number of digits in input,output and
- intermediate results won’t exceed 3000 digits.
- Expected Time Complexity:Let s1 and s2 be two big integers with n and m
- number of digits in them.Let x be an integer < 263
1) Addition(s1+s2) : O(n+m)
2) Subtraction(s1-s2) : O(n+m)
3) Multiplication(s1*s2) : O(n*m)
4) Division(s1/s2) : O(n*m)
5) Exponentiation(s1^x) : O(n*n*log(x))
6) GCD(s1,s2) : O(max(n,m))
7) Factorial(s1) : O( n3)

Cheers,  
Onkar Bharat Sawant  
M.Tech-CSE, IIIT Hyderabad
