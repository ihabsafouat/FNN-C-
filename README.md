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
./FNN2

```

##🧠 Neural Network Architecture
- Input Layer: 2 neurons (x, y)
- Hidden Layer 1: 8 neurons (ReLU)
- Hidden Layer 2: 4 neurons (ReLU)
- Output Layer: 1 neuron (Sigmoid, binary classification)

##🧪 What It Does
It generates 1000 random 2D points between [-2, 2]. The network learns to classify whether these points lie inside a unit circle centered at the origin.


##✅ Training Output 
```
EPOCH : 0  MSE : 0.117818
EPOCH : 100  MSE : 0.0111259
EPOCH : 200  MSE : 0.00738775
EPOCH : 300  MSE : 0.00588937
EPOCH : 400  MSE : 0.00434489
EPOCH : 500  MSE : 0.00364944
EPOCH : 600  MSE : 0.00321854
EPOCH : 700  MSE : 0.00290357
EPOCH : 800  MSE : 0.00266525
EPOCH : 900  MSE : 0.00246457

```
##📊 Test Output

```
 Test Results (1 = inside , 0 = outside) :
 point ( 0,0 ) :0.99814 ( actual : 1 , error : 0.00186006 )
 point ( 1,1 ) :2.7908e-12 ( actual : 0 , error : 2.7908e-12 )
 point ( 0.5,0.5 ) :0.995767 ( actual : 1 , error : 0.00423316 )
 point ( 2,0 ) :9.18604e-31 ( actual : 0 , error : 9.18604e-31 )

```

##📁 Project Structure
```
FNN2.cpp
FNN2.exe
README.md

```

## 📚 Topics Covered

- Feedforward Neural Networks

- Activation Functions (ReLU, Sigmoid)

- Backpropagation

- Gradient Descent

- Matrix Multiplication in C++

- He Weight Initialization
