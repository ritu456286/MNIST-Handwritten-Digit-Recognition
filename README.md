# MNIST Handwritten Digit Recognition

This repository contains a neural network implementation for recognizing handwritten digits from the MNIST dataset. The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits.

## Dataset

The MNIST dataset files are compressed in gzip format and include:

- **train-images-idx3-ubyte.gz**: Training set images (9912422 bytes)
- **train-labels-idx1-ubyte.gz**: Training set labels (28881 bytes)
- **t10k-images-idx3-ubyte.gz**: Test set images (1648877 bytes)
- **t10k-labels-idx1-ubyte.gz**: Test set labels (4542 bytes)

## Repository Contents

1. **Data Preparation**
   - Script to unzip the dataset and prepare it for training and testing.
   
2. **Neural Network Implementation**
   - Forward propagation implementation.
   - Training using Adam Optimizer.
   - Loss function using Cross Entropy.
   - Epoch-based training to minimize cost.
   - Prediction and accuracy evaluation.

## Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib (optional, for visualization)

You can install the necessary Python packages using pip:

```bash
pip install tensorflow numpy matplotlib
```
## Acknowledgements
 - The MNIST dataset is provided by Yann LeCun.
 - TensorFlow for the deep learning framework.
