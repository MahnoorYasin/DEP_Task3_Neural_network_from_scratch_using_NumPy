# MNIST Handwritten Digit Classification

This project implements a neural network from scratch using NumPy and Python to classify handwritten digits from the MNIST dataset. The model uses a simple feedforward neural network architecture and is trained using gradient descent optimization.

## Project Overview

The MNIST dataset is a well-known dataset in the field of machine learning. It contains 70,000 images of handwritten digits, each of size 28x28 pixels. This project aims to classify these images into their respective digits (0-9) using a neural network implemented from scratch.

## Model Architecture

The neural network architecture consists of the following components:

1. **Input Layer**: 784 neurons (28x28 pixels flattened into a 1D array).
2. **Hidden Layer**: 128 neurons with ReLU activation.
3. **Output Layer**: 10 neurons with Softmax activation, representing the 10 digit classes (0-9).

### Key Features

- **Data Preprocessing**: The images are normalized to ensure that the pixel values are between 0 and 1.
- **Weight Initialization**: Weights are initialized using a small random number scaled with He initialization to handle the ReLU activation.
- **Regularization**: L2 regularization is applied to prevent overfitting.
- **Visualization**: The project includes a function to visualize the predictions on a set of test images.

## Getting Started

### Prerequisites

To run this project, you'll need:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn

You can install the required packages using pip:

```bash
pip install numpy pandas matplotlib seaborn
.
