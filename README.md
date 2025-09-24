Numerical Methods C++ Programs

This repository contains C++ implementations of various numerical methods commonly used in engineering, mathematics, and scientific computing. Each program is self-contained and demonstrates a fundamental numerical technique.

Table of Contents

Bisection Method

Fixed Point Iteration

Newton–Raphson Method

Gauss Elimination

Gauss–Jordan Elimination

Jacobi Method

LU Decomposition

Matrix Inversion

Power Method

Monte Carlo Integration

Runge–Kutta 4th Order

Relaxation (SOR) Method

Simpson 1/3 Rule

Matrix Multiplication

1. Bisection Method

Purpose: Find a root of an equation f(x) = 0 using interval halving.
Inputs: Interval [a, b], tolerance.
Outputs: Approximate root.

2. Fixed Point Iteration

Purpose: Solve x = g(x) iteratively.
Inputs: Initial guess, tolerance, max iterations.
Outputs: Approximated root.

3. Newton–Raphson Method

Purpose: Solve f(x) = 0 using derivative-based iteration.
Inputs: Initial guess, tolerance, max iterations.
Outputs: Root approximation.

4. Gauss Elimination

Purpose: Solve a system of linear equations Ax = b.
Method: Forward elimination + back substitution.
Inputs: Augmented matrix.
Outputs: Solution vector x.

5. Gauss–Jordan Elimination

Purpose: Solve linear system Ax = b directly via Reduced Row Echelon Form (RREF).
Inputs: Augmented matrix.
Outputs: Solution vector x.

6. Jacobi Method

Purpose: Iteratively solve Ax = b using Jacobi iteration.
Inputs: Coefficient matrix A, constants b, initial guess, tolerance, max iterations.
Outputs: Approximate solution vector.

7. LU Decomposition

Purpose: Solve Ax = b by decomposing A = L * U.
Steps:

Decompose matrix into L (lower) and U (upper).

Forward substitution: Ly = b.

Back substitution: Ux = y.
Outputs: Solution vector and matrices L and U.

8. Matrix Inversion

Purpose: Find inverse of square matrix A using Gauss–Jordan elimination.
Inputs: Square matrix.
Outputs: Inverse matrix A^-1.

9. Power Method

Purpose: Find dominant eigenvalue and eigenvector of a matrix.
Inputs: Square matrix, initial guess vector, tolerance, max iterations.
Outputs: Largest eigenvalue and corresponding eigenvector.

10. Monte Carlo Integration

Purpose: Approximate definite integral ∫ f(x) dx using random sampling.
Inputs: Function f(x), limits a and b, number of random samples N.
Outputs: Estimated integral.

11. Runge–Kutta 4th Order (RK4)

Purpose: Solve first-order ODE dy/dx = f(x, y) with initial condition y(x0) = y0.
Inputs: Initial x0, y0, final x, step size h.
Outputs: Approximate y values at discrete points.

12. Relaxation (SOR) Method

Purpose: Solve Ax = b iteratively with relaxation factor ω to accelerate convergence.
Inputs: Coefficient matrix A, constants b, initial guess, omega, tolerance, max iterations.
Outputs: Approximate solution vector x.

13. Simpson 1/3 Rule

Purpose: Numerical integration using Simpson’s 1/3 formula.
Inputs: Function f(x), limits a and b, even number of intervals n.
Outputs: Estimated integral.

14. Matrix Multiplication

Purpose: Multiply two matrices C = A * B.
Inputs: Matrices A and B with compatible dimensions.
Outputs: Product matrix C.

Usage

Compile the C++ file: