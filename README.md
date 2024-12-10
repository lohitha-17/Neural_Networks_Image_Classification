# Neural Networks for Image Classification

## Overview
This project implements Artificial Neural Networks (ANNs) to classify images from two datasets:
- **MNIST Fashion**: Classification of grayscale images of clothing items into 10 categories.
- **CIFAR-10**: Classification of color images into 10 object categories.

## Objectives
- Build and train ANN models for both datasets.
- Optimize model performance through architecture tuning and hyperparameter optimization.
- Evaluate models using metrics like accuracy, confusion matrices, and classification reports.

## Datasets
- [MNIST Fashion](https://github.com/zalandoresearch/fashion-mnist)
- [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)

## Features
- Data normalization and preprocessing.
- Experimentation with ANN architectures (hidden layers, dropout, activation functions).
- Hyperparameter tuning using grid search.
- Model evaluation through classification reports and confusion matrices.

## Results
- **MNIST Fashion**:
  - Best Accuracy: **88%**
  - 
- **CIFAR-10**:
  - Best Accuracy: **47%**

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Matplotlib

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Neural_Networks_Image_Classification.git
   ```
2. Open `MNIST_Fashion_Classification.ipynb` or `CIFAR10_Classification.ipynb` in Jupyter Notebook or Colab.
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook to reproduce results.

## Challenges and Insights
- **Challenges**: Optimizing the CIFAR-10 model to achieve better accuracy due to its complexity.
- **Insights**: Hyperparameter tuning and architecture adjustments significantly improved performance on both datasets.
