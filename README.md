# Fashion-MNIST Image Classification using CNN with PyTorch

## 📌 Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the Fashion-MNIST dataset into 10 different clothing categories.

## 🎯 Objective

The objective of this project is to understand how a CNN can be used for image classification and to build, train, and evaluate a deep learning model using PyTorch.

## 📊 Dataset

Fashion-MNIST contains:

* 70,000 grayscale images
* Image size: 28 × 28 pixels
* 60,000 training images
* 10,000 testing images
* 10 clothing categories

### Classes

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

## 🧠 Model Architecture

The CNN model contains:

* Convolutional Layer 1
* ReLU Activation
* Max Pooling
* Convolutional Layer 2
* ReLU Activation
* Max Pooling
* Fully Connected Layers
* Output Layer with 10 classes

## ⚙️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* Google Colab

## 🔄 Workflow

1. Import required libraries
2. Check computing device
3. Load Fashion-MNIST dataset
4. Normalize image data
5. Create DataLoaders
6. Visualize sample images
7. Build CNN model
8. Define loss function and optimizer
9. Train the model
10. Evaluate the model on test data

## 📈 Model Performance

* Training Epochs: 2
* Final Training Accuracy: 85.14%
* Test Accuracy: **86.31%**

## 📁 Project File

`FashionMNIST_CNN.ipynb`

The complete implementation is available in the Jupyter Notebook included in this repository.

## 👨‍💻 Author

**Mohsin Hasan**

This project was created as part of my Data Analytics / Machine Learning learning journey.
