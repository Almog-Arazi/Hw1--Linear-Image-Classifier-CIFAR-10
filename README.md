## Linear Image Classifier - CIFAR-10

### Overview

This project is part of the **Deep Learning course at Reichman University**. It serves as an assignment focused on building Linear Classifier .

This project implements a **Linear Image Classifier** for a subset of the **CIFAR-10 dataset**. The primary objective is to classify images using a linear classifier while leveraging `NumPy` for efficient computation and exploring the benefits of **vectorized operations** in Python.

The project is divided into two main parts:

1. **Implementing loss functions, calculating gradients, and performing gradient descent.**
2. **Training and evaluating multiple classifiers.**

### Dataset

The dataset used is **CIFAR-10**, a well-known dataset consisting of **60,000 32x32 color images** in **10 classes** (such as airplanes, cars, birds, and more). However, in this implementation, we focus on only **two classes** to create a binary classification problem.

The dataset is automatically downloaded and preprocessed for training, validation, and testing.

### Project Structure

- **Data Loading & Preprocessing**  
  - Downloads the CIFAR-10 dataset (if not already available).  
  - Extracts and loads the dataset.  
  - Selects only two classes for a binary classification problem.  
  - Splits the dataset into **training, validation, and testing sets**.  

- **Linear Classifier Implementation**  
  - Implements **loss functions** such as:
    - **Hinge Loss** (for SVM)
    - **Softmax Loss** (for Logistic Regression)
  - Computes **gradients** using **analytical differentiation**.
  - Implements **gradient descent optimization**.

- **Model Training & Evaluation**  
  - Trains the model using gradient descent.
  - Evaluates performance using:
    - Accuracy
    - Loss analysis
    - Visualizing misclassified images

### Installation & Requirements

To run this notebook, you need Python 3 and the following dependencies:

```bash
pip install numpy matplotlib
```

### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Almog-Arazi/Linear-Image-Classifier-CIFAR10.git
   cd Linear-Image-Classifier-CIFAR10
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook "Linear Image Classifier-CIFAR-10.ipynb"
   ```

3. Run all cells to train and evaluate the classifier.

### Results & Analysis

- The notebook visualizes:
  - Sample images from the dataset.
  - Decision boundaries of the classifier.
  - Loss and accuracy trends over training epochs.

- **ALMOG ARZAI**

