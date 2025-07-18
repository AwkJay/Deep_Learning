# Week 1 - Day 1 Assignment
## Introduction to AI, Machine Learning, and Deep Learning

---

## Problem 1: Create a Softmax Function [2.5 Marks]

### Question:
Write a NumPy function `softmax(x)` that takes a 1D array `x` and returns its softmax probabilities.

The softmax for an element is defined as:

\[
\text{softmax}(x_i) = \frac{e^{x_i}}{\sum_j e^{x_j}}
\]

### Test Case:
Apply your function to the input array:

```python
x = np.array([1.0, 2.0, 3.0])
```

Print the result.

### Expected Output:
A probability distribution where all values sum to 1.0.

---

## Problem 2: Identify Which Problem is Which? [2.5 Marks]

### Question:
Given these examples, classify each as AI, ML, or DL by writing `print()` statements.

```python
examples = [
    "Self-driving car using CNNs",
    "Spam detection using Naive Bayes",
    "Expert system for medical diagnosis",
    "Face recognition using Siamese Networks",
    "Weather forecasting using linear regression"
]
```

### Task:
Use Python logic to classify them in your output.

---

## Problem 3: Intro to Colab, NumPy, and PyTorch [5 Marks]

### Question:

1. Generate a 5×5 random matrix with values between 0 and 1 using PyTorch.
2. Compute the following using PyTorch operations:
   - Mean
   - Standard Deviation
   - Sum
3. Convert the tensor to a NumPy array.
4. Recompute the same statistics using NumPy.

### Objective:
Understand basic tensor operations and interoperability between PyTorch and NumPy.

---

## Notes
- Ensure your code is clean and well-commented.
- Use proper variable names.
- Verify outputs for correctness.

