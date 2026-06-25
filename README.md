# 🤖 Mini GPT: Decoder-Only Transformer for Next Word Prediction

## 📖 Project Overview

This project implements a **Mini GPT (Generative Pre-trained Transformer)** using TensorFlow and Keras. It demonstrates the core concepts behind decoder-only Transformer models, including token embeddings, positional embeddings, masked self-attention, causal masking, autoregressive text generation, and next-word prediction.

The project is designed as an educational implementation to help understand how GPT models generate text one word at a time.

---

# 🎯 Objectives

* Understand Decoder-Only Transformer architecture.
* Learn masked self-attention and causal masking.
* Implement next-word prediction.
* Generate text using autoregressive decoding.
* Build a simplified GPT model from scratch.

---

# 🚀 Features

* Custom text dataset
* Tokenization and padding
* Vocabulary creation
* Token embedding
* Positional embedding
* Masked Multi-Head Self-Attention
* Decoder-only Transformer blocks
* Causal attention mask
* Next-word prediction
* Autoregressive text generation
* Educational step-by-step implementation

---

# 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy

---


---

# 🏗️ Model Architecture

```text
Input Text
     │
     ▼
Text Vectorization
     │
     ▼
Token + Position Embedding
     │
     ▼
Decoder Transformer Block
     │
     ▼
Decoder Transformer Block
     │
     ▼
Dense + Softmax
     │
     ▼
Next Word Prediction
```

---

# 🔄 Project Workflow

```text
Training Sentences
        │
        ▼
Text Tokenization
        │
        ▼
Create Input & Target Sequences
        │
        ▼
Token Embeddings
        │
        ▼
Positional Embeddings
        │
        ▼
Masked Multi-Head Self-Attention
        │
        ▼
Feed Forward Network
        │
        ▼
Predict Next Word
        │
        ▼
Generate Complete Text
```

# 🔮 Future Enhancements

* Train on larger datasets
* Beam Search and Top-k Sampling
* Temperature-based text generation
* Multi-layer Transformer architecture
* Fine-tuning on custom corpora
* Integration with Hugging Face Transformers
* Web interface using Streamlit
* REST API deployment

---

# 👨‍💻 Author

**Rushikesh Gade**

Artificial Intelligence | Deep Learning | Natural Language Processing Enthusiast

---


