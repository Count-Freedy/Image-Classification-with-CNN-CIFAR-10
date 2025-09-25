# Image Classification with CNN - MNIST & CIFAR-10

## Description
This project contains two image classification tasks using Convolutional Neural Networks (CNN):
MNIST: Classifying handwritten digit images (0-9) from grayscale 28x28 pixel images.
CIFAR-10: Classifying 32x32 color images across 10 real-world object categories including animals, vehicles, and more.
Both models are built using TensorFlow and Keras, trained on their respective datasets to achieve high classification accuracy.

## Features

1. MNIST :
   - Loads and preprocesses the MNIST handwritten digit dataset.
   - Builds and trains a CNN for digit classification.
   - Evaluates the model with high accuracy (> 99%).
   - Allows testing images and saving the model for reuse.

2. CIFAR-10
   - Loads and preprocesses CIFAR-10 color image dataset.
   - Builds a deeper CNN architecture for multi-class object classification.
   - Trains the CNN and evaluates performance on test data.
   - Visualizes sample predictions with input images and labels.

## Tech Stack
- Python 3.x
- TensorFlow 2.x (Keras API)
- NumPy
- Matplotlib

## How to Run
1. Clone the repository

2. Install dependencies:
   ```bash
   pip install tensorflow numpy matplotlib

3. Run the Jupyter notebooks or Python scripts for either MNIST or CIFAR-10 CNN models.

4. Follow the notebooks to train, evaluate, visualize predictions, and save models.

## Results
MNIST CNN achieves >99% accuracy on handwritten digit test data.
CIFAR-10 CNN achieves 72.55% accuracy on test images.
Visualizations show model predictions aligned with true labels, highlighting classification capabilities. 


