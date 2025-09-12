# Week 2 - Day 4 Assignment

## Implementing Transformers

Use Hugging Face transformers library to load models and tokenizers.

---

## Question 1: Load a Transformer Model and Tokenizer [2 marks]

### Tasks:

1. Choose any one Transformer model from the following:

   * `bert-base-uncased` (for attention demo)
   * `t5-small` (for summarization)
   * `Helsinki-NLP/opus-mt-en-hi` (for translation)

2. Load the selected model along with its tokenizer.

3. Print:

   * Model name
   * Total number of parameters

---

## Question 2: Simple Summarization using T5 [3 marks]

### Tasks:

1. Use `T5ForConditionalGeneration` and `T5Tokenizer`.

2. Summarize the following text:

"Natural Language Processing is a part of Artificial Intelligence that focuses on interaction between computers and human language. It enables applications like chatbots, translation, and summarization."

3. Prefix the input with:

```
summarize:
```

before tokenizing.

4. Print the final summarized output.

---

## Question 3: Print Number of Layers and Attention Heads in BERT [2 marks]

### Tasks:

1. Load the `bert-base-uncased` model.

2. Print:

   * Total number of encoder layers
   * Number of attention heads per layer

---

## Question 4: Tokenize and Decode a Sentence using BERT Tokenizer [3 marks]

### Tasks:

1. Use the `bert-base-uncased` tokenizer to tokenize the sentence:

"Transformers make NLP tasks easier."

2. Print:

   * Token IDs
   * Decoded tokens (words after tokenization)

---

## Notes

* Ensure correct usage of Hugging Face transformers APIs.
* Keep outputs clearly formatted.
* Verify tokenization and decoding steps carefully.
