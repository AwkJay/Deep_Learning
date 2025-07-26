# Day 2 Assignment
## Mathematics Foundations for Deep Learning

---

## Problem 1: Linear Algebra and Eigenvalues [3 Marks]

### Question:

1. Create two matrices:
   - Matrix A of shape (3×2)
   - Matrix B of shape (2×3)
   using `np.random.randint`

2. Multiply A and B and print the result.

3. Define the matrix:

\[
D = \begin{bmatrix} 4 & 2 \\ 1 & 3 \end{bmatrix}
\]

4. Find its eigenvalues and eigenvectors using NumPy.

5. Plot the eigenvectors using `matplotlib.pyplot.quiver`.

---

## Problem 2: Symbolic Differentiation and Gradient Step [3 Marks]

### Question:

1. Use `sympy` to define the function:

\[
f(x) = 3x^3 - 5x^2 + 2x - 1
\]

2. Find the derivative symbolically.

3. Evaluate the derivative at:

\[
x = 2
\]

4. Define the function:

\[
f(x, y) = x^2 + y^2
\]

5. Compute its gradient.

6. Perform one gradient descent step from:

\[
(x, y) = (3, 4)
\]

with learning rate = 0.1.

---

## Problem 3: Probability with Dice and Coin Simulation [4 Marks]

### Question:

1. Simulate rolling a fair die 1000 times using `numpy.random.randint`.

2. Plot a histogram of the results.

3. Print the empirical mean and variance.

4. Simulate a biased coin toss with:

\[
P(\text{heads}) = 0.7
\]

for 500 trials using `numpy.random.choice`.

5. Count the number of heads and tails.

6. Plot a bar chart of the outcomes.

---

## Notes

- Ensure your code is clean and well-structured.
- Use appropriate variable names.
- Verify correctness of numerical results.

