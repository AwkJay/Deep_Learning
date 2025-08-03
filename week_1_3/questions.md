# Week 1 - Day 3 Assignment

Use only NumPy, Matplotlib, and Scikit-learn — no deep learning libraries.

---

## Problem 1: Data Preparation [2 marks]

### Question:
Use the Iris dataset.

### Tasks:

1. Load the dataset using `load_iris()`.
2. Extract features `X` and labels `y`.
3. One-hot encode the labels using `OneHotEncoder`.
4. Normalize the features using `StandardScaler`.
5. Split the dataset into training and testing sets:
   - `X_train`, `X_test`, `y_train`, `y_test`
   - Test size = 0.2
6. Print the shapes of `X_train`, `X_test`, `y_train`, and `y_test`.

---

## Problem 2: Activation Function [2 marks]

### Question:
Paste the `get_activation_funcs()` function provided in class.

### Steps:

1. Call it for the following activation functions:
   - "sigmoid"
   - "relu"
2. Pass the input:

```python
np.array([[0, 1, -1]])
```

3. Print the outputs to observe their behavior.

---

## Problem 3: Train the MLP Model on Iris Data [3 marks]

### Question:
Paste and use the `train_model(activation_name)` function provided in class.

### Steps:

1. Train the model using the following activation functions:
   - "sigmoid"
   - "tanh"
   - "relu"
   - "leaky_relu"

2. Plot loss curves using `matplotlib`.

3. Display test accuracy in the plot legend.

---

## Problem 4: Report Accuracy of Each Activation [2 marks]

### Steps:

1. Store test accuracies in a dictionary, for example:

```python
accuracies = {
    "sigmoid": 0.89,
    "tanh": 0.91,
    "relu": 0.93,
    "leaky_relu": 0.92
}
```

2. Print the dictionary after training.

---

## Problem 5: Predict Class of a New Sample [1 mark]

### Given:

```python
sample = np.array([[5.1, 3.5, 1.4, 0.2]])
```

### Steps:

1. Normalize the sample using the same `StandardScaler` from Problem 1.
2. Pass it to the trained `predict()` function (from `train_model`).
3. Print the predicted class index (0, 1, or 2).

---

## Notes

- Follow the constraint of not using deep learning libraries.
- Keep code modular and well-structured.
- Ensure reproducibility where possible.

