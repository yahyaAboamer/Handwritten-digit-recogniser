# **Handwritten Digit recogniser**

## **📌 Project Overview**

This project implements a handwritten digit classifier using the MNIST dataset with a Deep Neural Network (DNN) built in TensorFlow/Keras. The model is trained using the Sequential API and evaluated with various metrics.

## **📂 Dataset: MNIST**

MNIST is a dataset of 70,000 grayscale images (28x28 pixels) of handwritten digits (0-9).

It is divided into 60,000 training images and 10,000 test images.

Each image corresponds to a label (digit from 0 to 9).

## **🏗️ Model Architecture**

The model consists of:

Flatten Layer: Converts 2D images into a 1D vector.

Dense Layer (300 neurons, ReLU activation)

Dense Layer (100 neurons, ReLU activation)

Output Layer (10 neurons, Softmax activation): Outputs probabilities for digits 0-9.

## **⚙️ Training and Optimization**

Loss Function: Sparse Categorical Crossentropy

Optimizer: Stochastic Gradient Descent (SGD)

Metrics: Accuracy

Epochs: 30

## **📊 Evaluation Metrics**

To assess the model's performance, we use:

Accuracy: Measures correct predictions.

Training History Plot: Visualizes accuracy and loss over epochs.

Predictions on Test Samples: Compares actual vs. predicted values.

## **🚀 How to Run the Code**

Install dependencies:

pip install tensorflow numpy matplotlib pandas

Run the Jupyter Notebook or Google Colab file.

Train the model and evaluate its performance.

View training history and classification accuracy.
