# MNIST Handwritten Digit Classification

This project implements a simple neural network from scratch using NumPy and Python to classify handwritten digits from the MNIST dataset.

## Project Overview

The MNIST dataset is a widely recognized benchmark in machine learning, consisting of 70,000 images of handwritten digits, each of size 28x28 pixels. The objective of this project is to correctly classify these images into their respective digits (0-9) using a feedforward neural network.

## Features

- **Data Preprocessing**: The dataset is normalized to ensure pixel values are between 0 and 1, which helps in speeding up the training process.
  
- **Neural Network Architecture**: 
  - **Input Layer**: 784 neurons, each corresponding to a pixel in the input image.
  - **Hidden Layer**: A single hidden layer with 128 neurons using ReLU activation for introducing non-linearity.
  - **Output Layer**: 10 neurons with Softmax activation for multi-class classification, representing each digit from 0 to 9.

- **Training**: The network is trained using gradient descent with backpropagation for parameter updates. L2 regularization is also implemented to prevent overfitting.

- **Testing**: The trained model is evaluated on a development set to measure its accuracy in predicting handwritten digits.

- **Visualization**: A function is provided to visualize predictions against true labels for a subset of the test data, helping to visually assess model performance.

## Results

The model achieves an accuracy of approximately 90% on the development set, demonstrating the effectiveness of this simple neural network in digit classification tasks.

## Getting Started

### Prerequisites

To run this project, you need the following packages:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn

Install the required packages using pip:

```bash
pip install numpy pandas matplotlib seaborn
```

### Running the Project

**Download the MNIST Dataset**

   Ensure you have the MNIST dataset in CSV format, typically found on [Kaggle](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv).


## Conclusion

This project showcases a basic yet effective approach to building a neural network from scratch using Python and NumPy. It's a great starting point for understanding the mechanics behind neural networks and the MNIST classification problem.

## Future Improvements

- **Adding More Layers**: Experiment with deeper architectures to potentially improve accuracy.
- **Advanced Techniques**: Implement dropout, learning rate schedules, or other optimization methods.
- **Transfer Learning**: Explore pre-trained models or CNN architectures for better performance.
