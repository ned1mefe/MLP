# CerGen - Custom Neural Network Library

CerGen is a minimal deep learning library implemented **from scratch in Python**, without using external libraries like NumPy, PyTorch, or TensorFlow. This project is developed as part of the CENG 403 Take-Home Exam 2 and demonstrates a deep understanding of tensor operations, automatic differentiation, and neural network training.

You can use Google Colab to run: https://colab.research.google.com/drive/14Iwi2to7NWlAaPoXDvwzeqn4wRsYyqvw

## 📌 Features

- Custom `Tensor` class with:
  - Broadcasting support
  - Forward and backward operations for addition, multiplication, matrix multiplication, etc.
  - Autograd functionality with a `geri()` method (manual reverse-mode autodiff)
- Layer implementations:
  - `Linear` (fully-connected) layers
  - Activation functions: `ReLU`, `Softmax`
- Loss function:
  - Cross-entropy loss with automatic gradient computation
- A simple `MLP` (Multi-Layer Perceptron) architecture
- MNIST training from raw CSV data (without any external libraries)

