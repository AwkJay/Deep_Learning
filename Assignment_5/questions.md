# Week 1 - Day 5 Assignment

Marks: 10
Tools: TensorFlow (with Keras backend) and PyTorch

---

## Problem Statement

Implement a single-layer neural network with the following specifications:

* Input: shape (1, 3)
* Weights: shape (3, 1) (initialize manually)
* Bias: scalar or shape (1,)
* Activation: Sigmoid
* Loss: Binary Cross-Entropy
* Ground truth label: ( y_{true} = 1.0 )

---

## Task 1: TensorFlow (Keras backend) [5 marks]

### Instructions:

1. Manually initialize weights and bias using `tf.Variable`.
2. Compute the linear combination:

[
z = XW + b
]

using `tf.matmul`.

3. Apply sigmoid activation using `tf.math.sigmoid`.

4. Compute Binary Cross-Entropy loss manually:

[
\text{loss} = -\left(y \cdot \log(\hat{y}) + (1 - y) \cdot \log(1 - \hat{y})\right)
]

---

## Task 2: PyTorch [5 marks]

### Instructions:

1. Manually initialize weights and bias using `torch.tensor`.
2. Compute the linear combination:

[
z = XW + b
]

using `torch.mm`.

3. Apply sigmoid activation using `torch.sigmoid`.

4. Compute Binary Cross-Entropy loss manually using the same formula.

5. Call `.backward()` and print gradients of the weights.
