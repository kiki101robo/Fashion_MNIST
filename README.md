# FashionMNIST Classification with PyTorch

## Project Overview
This repository contains a machine learning project that utilizes PyTorch to classify images from the FashionMNIST dataset. The project explores several neural network architectures to identify different clothing items from the dataset, which includes 10 different classes such as T-shirts/tops, Trousers, Pullovers, Dresses, Coats, Sandals, Shirts, Sneakers, Bags, and Ankle boots.

## Features
- **Data Loading**: Automated downloading and loading of FashionMNIST using PyTorch's `torchvision` module.
- **Neural Network Implementations**:
  - Basic Neural Network with linear layers.
  - Advanced Neural Network with ReLU activation.
  - Convolutional Neural Network (CNN) for capturing spatial hierarchies in images.
- **Model Training and Validation**: Code to train and validate models using training and test datasets.
- **Performance Visualization**: Scripts to visualize training performance and test results including confusion matrices.
- **Utility Functions**: Includes helper functions for model evaluation and prediction.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or newer
- PyTorch 1.7 or newer
- Torchvision
- NumPy
- Matplotlib
- tqdm

You can install the required packages using the following command:
```bash
pip install torch torchvision numpy matplotlib tqdm
Installation
Clone this repository to get started with the project:

bash
Copy code
git clone https://github.com/your-repository/fashion-mnist-classification.git
cd fashion-mnist-classification
Running the Scripts
To run the main project script, execute the following in the command line:

bash
Copy code
python fashion_mnist_classification.py
Models
This project includes several model architectures:

FashionMNIST: Basic linear neural network model.
FashionMNIST1: Improved model with ReLU activations.
CNNFM: A more complex convolutional neural network designed to achieve higher accuracy on image data.
Results
Models are evaluated using accuracy metrics and confusion matrices to understand their performance on both training and testing data. The results are printed during script execution and can be visualized using Matplotlib plots included in the scripts.
