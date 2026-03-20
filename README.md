# Transformer and Neural Network from Scratch

## Overview
This project implements:
- Logistic Regression (baseline)
- Neural Network from scratch using NumPy
- Transformer Encoder from scratch using PyTorch

---

## Dataset
The dataset used is:
- `nsp_electricity_dataset.csv`

Target column:
- `anomaly_flag` (binary classification)

---

## Part 1: Backpropagation

### Steps:
- Data preprocessing (handling categorical variables, scaling)
- Train/test split (80/20)
- Logistic Regression baseline
- Neural Network implemented from scratch:
  - Forward propagation
  - Sigmoid activation
  - Backpropagation
  - Gradient descent

---

## Part 2: Transformer

### Task:
Reverse a sequence of integers  
Example:
Input: [3, 5, 2, 4, 1]  
Output: [1, 4, 2, 5, 3]

---

### Implementation:
Built from scratch using PyTorch:
- Token Embedding (manual)
- Positional Embedding
- Self-Attention
- Feed Forward Network
- Layer Normalization


## Evaluation

The model partially learns the sequence reversal task but does not achieve perfect accuracy due to:
- Limited training epochs
- Small model size
- Simplified architecture

---