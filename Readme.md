# 🚀 Transformer From Scratch (PyTorch)

> Built a complete Transformer architecture from scratch using PyTorch — without relying on high-level libraries.

---

## 🧠 Overview

This project is a **ground-up implementation of the Transformer architecture** introduced in the paper:

👉 "Attention Is All You Need"

Instead of using pre-built modules, every core component has been implemented manually to deeply understand how Transformers work internally.

---

## 🔥 What’s Implemented

### ✅ Multi-Head Self Attention
- Query, Key, Value projections
- Parallel attention heads
- Scaled dot-product attention
- Masking support

---

### ✅ Transformer Block
- Multi-head attention
- Add & Layer Normalization
- Feed Forward Network (FFN)
- Dropout for regularization

---

### ✅ Positional Encoding
- Sinusoidal positional encoding
- Injects sequence order into embeddings

---

### ✅ Encoder
- Token embedding + positional encoding
- Stack of Transformer blocks
- Context-aware representations

---

### ✅ Decoder Block
- Masked self-attention (causal masking)
- Cross-attention (Encoder → Decoder connection)
- Add & Norm layers

---

## 🧠 Key Learnings

- How attention actually computes relationships between tokens
- Why multi-head attention improves learning capacity
- Importance of masking (padding + causal)
- Role of residual connections & normalization
- Difference between encoder and decoder behavior

---

## 📐 Architecture Flow

---

## 🛠️ Tech Stack

- Python
- PyTorch
- NumPy
- Math (for positional encoding)

---

## 🚀 Future Work

- Full Decoder implementation
- Complete Transformer model (Encoder + Decoder)
- Training on real dataset (translation / summarization)
- Build mini GPT (decoder-only model)

---

## 🙏 Acknowledgment

Huge thanks to **Mr. Tanmoy Chakraborty** for guiding and inspiring this learning journey.

---

## ⭐ If you found this helpful

Give this repo a ⭐ and connect with me on LinkedIn!
