# Week 2 - Day 2 Assignment

## Advanced CNNs – Transfer Learning and Pre-trained Models (ResNet, VGG)

Use only TensorFlow/Keras for model-related tasks.

---

## Question 1: Load and Freeze VGG16 [3 marks]

### Tasks:

Write Python code to:

1. Load the VGG16 model with pretrained weights:

   * `weights='imagenet'`
   * `include_top=False`

2. Freeze all layers of the model.

3. Print:

   * Number of trainable parameters
   * Number of non-trainable parameters

---

## Question 2: Compare Output Shapes of VGG16 and ResNet50 [3 marks]

### Tasks:

Write Python code to:

1. Load a sample image and resize it to 224 × 224.
2. Preprocess the image appropriately.
3. Pass the image through:

   * VGG16 (`include_top=False`)
   * ResNet50 (`include_top=False`)
4. Print the output feature map shapes from both models.

---

## Question 3: Use ResNet50 for Classification [4 marks]

### Tasks:

Write Python code to:

1. Load the ResNet50 model with:

   * `include_top=True`
   * Pretrained ImageNet weights

2. Load a sample image, resize and preprocess it correctly.

3. Use the model to predict the class.

4. Display the top 3 predictions using `decode_predictions`.
