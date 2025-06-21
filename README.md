# 🧠 Neural Network from Scratch – MNIST Digit Classifier

This project implements a simple neural network **from scratch using NumPy and Pandas** to classify handwritten digits from the **MNIST dataset**. It is designed as a learning tool to help you understand the internals of how a feedforward neural network works without relying on high-level machine learning libraries like TensorFlow or PyTorch.

---

## 🔍 Overview

- Architecture:  
  - Input layer: 784 neurons (28×28 pixels flattened)  
  - Hidden layer: 64 neurons, sigmoid activation  
  - Output layer: 10 neurons, softmax activation
- Loss: Categorical Cross-Entropy
- Optimizer: Mini-batch Gradient Descent

---

## 🏗️ Features

- Full forward and backward pass using matrix operations
- Cross-entropy loss with softmax output
- One-hot encoding using `pandas.get_dummies()`
- No deep learning libraries — only `NumPy`, `Pandas`, and `Matplotlib`
- Accuracy and loss tracking over epochs
- Easy-to-extend design (add layers, change activations, etc.)

---

## 📦 Requirements

Install Python dependencies:

```bash
pip install numpy pandas matplotlib tensorflow
```
Note: We use tensorflow.keras.datasets just to load the MNIST data.🚀 How to Run

---

## 🧠 Neural Network Architecture

Input (784) → W1 + b1 → Hidden (64, sigmoid) → W2 + b2 → Output (10, softmax)

---

## 📌 Notes

- You can switch to ReLU by changing activation functions.
- Extend to multiple hidden layers by adding more forward/backward logic.
- This is a CPU-based implementation and may be slow on large datasets.

