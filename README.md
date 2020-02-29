# polynomial_roots
This Jupyter notebood presents a Python code for an algorithm that finds all the real roots of a polynomial, 
using the roots of its derivative to obtain isolating intervals. Roots of the derivative are found by 
recursive applications of the method, until a first degree polynomial is found. We present arbitrary precision 
mpmath Python code for the algorithm, and tests with notorious polynomials.
