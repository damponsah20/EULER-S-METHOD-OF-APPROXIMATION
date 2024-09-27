# Euler's Method Approximation

Euler's method is a simple numerical technique for solving ordinary differential equations (ODEs) of the form:

\[
\frac{dy}{dx} = f(x, y)
\]

Given an initial value \( y(x_0) = y_0 \), Euler's method approximates the solution of the ODE by stepping forward in small increments.

### Euler's Method Formula:

For a given step size \( h \), the approximation is:
\[
y_{n+1} = y_n + h \cdot f(x_n, y_n)
\]

### Example:

Consider the ODE:
\[
\frac{dy}{dx} = x + y
\]
with the initial condition \( y(0) = 1 \) and step size \( h = 0.1 \).

1. Start at \( (x_0, y_0) = (0, 1) \).
2. Calculate the next value:
   \[
   y_1 = y_0 + h \cdot f(x_0, y_0) = 1 + 0.1 \cdot (0 + 1) = 1.1
   \]
3. Update \( x_1 = x_0 + h = 0 + 0.1 = 0.1 \).

This process is repeated to approximate the solution.
