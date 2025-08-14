# Week 1 - Day 4 Assignment

---

## Instructions

---

## Question 1: Compare the Loss Functions [5 marks]

### Objective:
Train a single-layer neural network using different loss functions for regression and classification.

### Dataset:

- Use `make_regression` for regression
- Use `make_classification` for binary classification

### Instructions:

1. Implement a single neuron (no hidden layers).
2. For regression:
   - Use Mean Squared Error (MSE)
   - Do not use any activation function
3. For classification:
   - Use Binary Cross Entropy (BCE)
   - Use sigmoid activation
4. Train the model using gradient descent.
5. Plot loss versus epochs for both cases.

---

## Question 2: Compare the Learning Rate Effects [5 marks]

### Objective:
Understand how different learning rates affect model training.

### Dataset:

- Use `make_classification(n_features=2)`

### Instructions:

1. Use sigmoid activation and Binary Cross Entropy (BCE).
2. Try the following learning rates:
   - 0.01
   - 0.1
   - 1
3. Train using gradient descent for 100 epochs.
4. Plot loss curves for each learning rate.
5. Observe and describe how learning rate affects:
   - Speed of convergence
   - Stability of training

---

## Notes

- Keep implementations simple and from scratch where possible.
- Ensure clear visualization of loss curves.
- Comment your code for clarity.

