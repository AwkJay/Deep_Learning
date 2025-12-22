# Week 3 - Day 2 Assignment

## Implement and Analyze a Denoising Diffusion Probabilistic Model (DDPM)

Total Marks: 10


---

## Question 1: Forward Diffusion Process on MNIST Digits [3 marks]

### Tasks:

1. Simulate a forward diffusion process by adding Gaussian noise to MNIST digit images over 200 timesteps.
2. Display visual samples at timesteps:

   * t = 1, 50, 100, 150, 200
3. Plot variance (noise level) versus timestep.
4. Implement all operations manually using tensor-level operations, including:

   * Noise addition
   * Beta schedule

---

## Question 2: Backward Denoising with a Simple Model [4 marks]

### Tasks:

1. Build a minimal denoising model:

   * Simple linear model or 2-layer MLP
   * Use only tensor operations such as `torch.matmul`

2. Train the model to reverse noise from the forward process:

   * Predict original image or noise
   * Use timestep information as input

3. Use Mean Squared Error (MSE) loss.

4. Display denoising results for timesteps:

   * t = 200 → 0

5. Plot the training loss curve.

---

## Question 3: Class-Conditional Diffusion [1 mark]

### Tasks:

1. Condition the denoising model on MNIST digit labels:

   * Use one-hot encoding of labels
   * Concatenate with model input

2. Show generated/denoised outputs conditioned on classes:

   * 0, 1, 2

---

## Question 4: Text-to-Image with Pretrained Stable Diffusion [2 marks]

### Tasks:

1. Load a Stable Diffusion pipeline using Hugging Face.

2. Generate images for example prompts such as:

   * "A cat playing piano"
   * "A fantasy castle at night"

3. Display the generated images.

