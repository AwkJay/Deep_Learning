# Week 2 - Day 3 Assignment

## Practical Assignment – RNN for Temperature Prediction

Total Marks: 10
Level: Beginner (Post First RNN Session)
Dataset: Daily Climate Time Series Data ([https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data))

Column to Predict: MeanTemp

---

## Objective

Use Recurrent Neural Networks (RNN) to learn patterns in daily temperature data and predict the next day’s mean temperature based on the last 30 days.

---

## Tasks and Marking Scheme

### 1. Load and Inspect Data [1 mark]

#### Tasks:

1. Load the dataset using Pandas.
2. Display information about the dataset.
3. Plot the `MeanTemp` column over time using matplotlib.

#### Marks:

* 0.5 for correct loading
* 0.5 for visualization

---

### 2. Preprocess the Data [2 marks]

#### Tasks:

1. Extract the `MeanTemp` column.
2. Normalize it using `MinMaxScaler`.
3. Plot the data before and after normalization.

#### Marks:

* 1 for clean extraction and scaling
* 1 for plotting and comparison

---

### 3. Create Sequences for Prediction [2 marks]

#### Tasks:

1. Write a function:

```python
def create_sequences(data, seq_length=30):
    pass
```

2. Split data into:

   * `x`: sequences of 30 time steps
   * `y`: next value

3. Reshape `x` to shape:

```
(samples, 30, 1)
```

#### Marks:

* 1.5 for working function and correct shapes
* 0.5 for clear code explanation

---

### 4. Build and Compile an RNN Model [2 marks]

#### Tasks:

1. Build a model using:

   * `SimpleRNN(units=50, return_sequences=False)`
   * `Dense(1)` output layer

2. Compile the model with:

   * Loss: `mean_squared_error`
   * Optimizer: `adam`

3. Print the model summary.

#### Marks:

* 1 for correct architecture
* 1 for compilation and summary

---

### 5. Train the Model and Visualize Loss [1.5 marks]

#### Tasks:

1. Train the model for 10 epochs with `batch_size=32`.
2. Use `validation_split=0.2`.
3. Plot training and validation loss.

#### Marks:

* 1 for training
* 0.5 for loss plot

---

### 6. Evaluate Model and Plot Predictions [1.5 marks]

#### Tasks:

1. Predict on the test set.
2. Inverse transform both predicted and true values.
3. Plot predicted vs actual temperatures (first 50 points).

#### Marks:

* 0.5 for prediction code
* 1 for correct and labeled plot
