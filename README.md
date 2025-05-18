# 🔵 Neural Network in C++ from Scratch

This project implements a basic **feedforward neural network** in **C++** without any external machine learning libraries. It uses ReLU and Sigmoid activation functions and supports training via **backpropagation**.

The example provided trains the network to **classify whether a point lies inside a unit circle** (`sqrt(x² + y²) < 1`).

---

## 📌 Features

- Multilayer Perceptron (MLP) with 3 layers (2 hidden)
- ReLU and Sigmoid activation functions
- Mean Squared Error (MSE) loss function
- Fully custom forward and backward propagation
- Matrix class for simple matrix operations
- Random weight initialization (He initialization)
- Performance benchmark (training time)
- No external ML libraries required

---

## 🚀 Getting Started

### ✅ Requirements

- C++11 or newer
- g++ / clang++ or any modern C++ compiler

### 🛠️ Compilation

To compile:

```bash
g++ -std=c++11 -O2 main.cpp -o neural_net
```
