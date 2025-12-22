# Week 1 - Weekend Assignment

## DL Summer Camp Assignment

Max Marks: 20

---

## Question 1: Introduction to AI/ML/DL [1 mark]

### Tasks:

1. Load a pre-built dataset using `sklearn.datasets` (e.g., Iris, Wine, or Digits).

2. Build three classifiers:

   * Logistic Regression (Machine Learning)
   * Decision Tree (AI rule-based)
   * Simple 1-hidden-layer Neural Network (Deep Learning)

3. For each model:

   * Print accuracy
   * Print confusion matrix

4. Write a markdown comment:

   * What makes the Neural Network different in behavior compared to the others?

---

## Question 2: Mathematics for Deep Learning [4 marks]

### Tasks:

1. Implement the following:

   * Matrix multiplication (3×3)
   * Determinant and inverse (if it exists)
   * Eigenvalues and eigenvectors

2. Plot the following functions and their derivatives:

   * ( f(x) = x^2 + 3x + 2 )
   * ( \sigma(x) ) (sigmoid function)

3. Simulate discrete probability distributions:

   * ( P = [0.2, 0.5, 0.3] )
   * ( Q = [1/3, 1/3, 1/3] )

4. Compute:

   * Cross Entropy
   * KL-Divergence

---

## Question 3: Neural Networks Basics [4 marks]

### Tasks:

1. Implement a custom perceptron using only NumPy.

2. Train it on a linearly separable binary dataset (e.g., AND, OR).

3. Visualize:

   * Input points
   * Decision boundary

4. Add ReLU and Sigmoid activation functions and observe how they change the output space.

---

## Question 4: Training Neural Networks [6 marks]

### Dataset:

Create a synthetic regression dataset:

[
Y = 2.5X + \sin(X) + \text{noise}, \quad X \in [0, 10]
]

### Tasks:

1. Build a neural network with:

   * 2 Dense layers
   * ReLU activation
   * Mean Squared Error (MSE) loss

2. Train the model using:

   * SGD
   * Adam
   * RMSProp

3. For each optimizer:

   * Plot loss curve
   * Compare RMSE

4. Conclude:

   * Which optimizer performs best and why?

---

## Question 5: Deep Learning Frameworks [4 marks]

### Tasks:

1. Implement the same small CNN for MNIST using:

   * TensorFlow + Keras
   * PyTorch

2. Compare:

   * Number of lines of code
   * Syntax clarity
   * Model summary

3. Print test accuracy for both implementations.

4. Write a markdown cell:

   * Which framework do you prefer and why?