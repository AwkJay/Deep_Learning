# Week 2 - Day 6 Assignment

## Practical Assignment: Introduction to Large Language Models (LLMs)

Total Marks: 10

---

## Objective

To explore the basics of working with Large Language Models using pre-trained models from Hugging Face.

---

## Task 1: Text Generation using GPT-2 [2 marks]

### Tasks:

1. Load GPT-2 using Hugging Face's `pipeline`.
2. Use the prompt:

"The future of AI is"

3. Generate a continuation of up to 30 tokens.

---

## Task 2: Experiment with Temperature [2 marks]

### Tasks:

1. Use the same prompt as in Task 1.
2. Generate outputs with two temperature settings:

   * `temperature = 0.2`
   * `temperature = 1.0`
3. Observe and print both outputs.

---

## Task 3: Fill-in-the-Blank using BERT [2 marks]

### Tasks:

1. Use `bert-base-uncased` with Hugging Face's `fill-mask` pipeline.
2. Predict the masked token in the sentence:

"The capital of India is [MASK]."

3. Display the top 2 predictions.

---

## Task 4: Mock Tool Call Output [2 marks]

### Tasks:

Simulate a structured tool call in JSON format for the query:

"Check weather in Delhi"

Output the following structure:

```json
{
  "function": "get_weather",
  "arguments": {
    "city": "Delhi"
  }
}
```

---

## Task 5: Analyze Model Configuration [2 marks]

### Tasks:

1. Load the GPT-2 model using:

   * `AutoModelForCausalLM`
   * `AutoTokenizer`

2. Print:

   * Number of parameters in the model
   * Model configuration (`config`)