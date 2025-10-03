#Neural Network – MNIST

##This repository demonstrates how to build and train a neural network for the MNIST handwritten digit classification task in two different ways:

    ###From Scratch (with NumPy)

    ###Using TensorFlow (high-level API)

## Project Structure
###1. MNIST Handwritten (NumPy Implementation)

A neural network is built entirely from scratch using only the numpy library.

Every layer (Dense, ReLU, Softmax, etc.) is hand-written with mathematical logic.

No external ML libraries like TensorFlow or PyTorch are used.

The code is written in a beginner-friendly style, with step-by-step explanations, starting from what MNIST is all the way to computing the final accuracy.

###2. MNIST TensorFlow Version

The same model is implemented using TensorFlow’s high level API (tensorflow.keras).

No manual math or backpropagation is required, TensorFlow handles it internally.

The code is much shorter and cleaner, showing how you’d typically build models once you understand the basics.

## Learning Goals

Understand how a neural network works under the hood.

Learn forward propagation, backpropagation, loss functions, and optimizers by coding them manually.

Transition smoothly to real-world ML frameworks like TensorFlow.

## Dataset

MNIST dataset: 70,000 grayscale images of handwritten digits (0–9).

Each image is 28×28 pixels → flattened into 784 features.

Available from OpenML
, Keras datasets, or Kaggle.