# Week 3 - Day 3 Assignment

## Explainable AI

---

## Instructions

* All problems are compulsory.
* Use the LIME library (`lime.lime_tabular` and/or `lime.lime_image`) for explanations.

---

## Question 1: LIME for Tabular Model Explanation [5 marks]

### Tasks:

1. Load a structured dataset (e.g., Iris, Titanic, Breast Cancer from `sklearn` or `seaborn`).

2. Train a classification model:

   * Logistic Regression, or
   * Decision Tree

3. Apply LIME on one test sample to generate a local explanation.

4. Display the following:

   * Feature contribution plot (from LIME)
   * Top 3 contributing features
   * Predicted class

---

## Question 2: LIME for CNN Image Explanation [5 marks]

### Tasks:

1. Load an image dataset such as:

   * MNIST
   * Fashion MNIST
   * CIFAR-10

2. Build and train a small CNN model with at most 2 convolutional layers on a subset of the data.

3. Select one test image and apply LIME for image classification.

4. Display the following:

   * Superpixel segmentation with class prediction explanation
   * LIME visualization (save and display)

---

## Notes

* Ensure correct integration of LIME with both tabular and image data.
* Keep model architectures simple and interpretable.
* Clearly visualize and explain the outputs.
