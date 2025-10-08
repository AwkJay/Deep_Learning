# Week 3 - Day 1 Assignment

## Training GAN for Data Augmentation

Assignment: Implement a GAN
Total Marks: 10

Languages Allowed: Python using only NumPy, Matplotlib, and basic PyTorch/TensorFlow for tensor operations (no use of high-level APIs such as `nn.Sequential`, `Model`, etc.)

---

## Question 1: Manual Forward Pass and Backpropagation in Generator and Discriminator [4 marks]

### Tasks:

1. Manually implement forward and backward passes of a GAN using low-level tensor operations.

2. Initialize weights manually for:

   * Generator with two hidden layers
   * Discriminator with two hidden layers

3. Use the following activations:

   * Discriminator: LeakyReLU
   * Generator: ReLU and Tanh

4. Use Binary Cross Entropy loss.

5. Write custom training loops to update weights using SGD or Adam.

6. Use real data from:

   * MNIST dataset, or
   * A simulated dataset (e.g., blobs)

7. Display results:

   * Plot loss curves for generator and discriminator
   * Show sample generated images at epochs: 5, 50, 100, 200

---

## Question 2: Generate Augmented Data [3 marks]

### Tasks:

1. Use the trained generator to create new data for a minority class.

2. Generate at least 1000 synthetic images for a selected class (e.g., '1' or '5').

3. Save the generated images and visually verify diversity.

4. Combine synthetic data with the original dataset to create a balanced dataset.

---

## Question 3: Train a Classifier on Original vs Augmented Dataset [3 marks]

### Tasks:

1. Manually implement a 2-layer classifier using only:

   * `torch.matmul` or
   * `tf.matmul`

2. Train the classifier on the original dataset and evaluate performance.

3. Train the classifier on the augmented dataset and compare results.

4. Evaluate using metrics such as:

   * Accuracy
   * Precision and recall
   * Confusion matrix
