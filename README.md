## Neural Networks - CIFAR-10

### Overview

This project is part of the **Deep Learning course at Reichman University**. It serves as an assignment focused on building and understanding neural networks.

This project implements a **Three-Layer Neural Network Classifier** for the **CIFAR-10 dataset**. The goal is to classify images into multiple categories using a **fully connected neural network**, implemented from scratch using `NumPy`. The focus is on **forward propagation, backpropagation, and training using gradient descent**.

The project is divided into two main parts:

1. **Implementing forward and backward propagation for a multi-class neural network.**
2. **Training and evaluating the neural network on CIFAR-10.**

### Dataset

The dataset used is **CIFAR-10**, a well-known dataset consisting of **60,000 32x32 color images** in **10 classes** (such as airplanes, cars, birds, and more). The dataset is automatically downloaded and preprocessed for training, validation, and testing.

### Project Structure

- **Data Loading & Preprocessing**  
  - Downloads the CIFAR-10 dataset (if not already available).  
  - Extracts and loads the dataset.  
  - Selects a subset of classes for training.  
  - Splits the dataset into **training, validation, and testing sets**.  

- **Neural Network Implementation**  
  - Implements **forward propagation** for multi-class classification.
  - Implements **backpropagation** using gradient descent.
  - Defines **activation functions**, **loss functions**, and **optimization methods**.

- **Model Training & Evaluation**  
  - Trains the neural network with gradient descent.
  - Evaluates performance using:
    - Accuracy
    - Loss analysis
    - Visualizing sample classifications


### Installation & Requirements

To run this notebook, you need Python 3 and the following dependencies:

```bash
pip install numpy matplotlib
```

### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Almog-Arazi/Neural-Networks-CIFAR10.git
   cd Neural-Networks-CIFAR10
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook "Neural Networks -CIFAR-10.ipynb"
   ```

3. Run all cells to train and evaluate the neural network.

### Results & Analysis

- The notebook visualizes:
  - Sample images from the dataset.
  - Neural network decision boundaries.
  - Loss and accuracy trends over training epochs.


### Author

**Almog Arazi**
