#Handwritten Digit recogniser

📌 Project Overview

This project implements a handwritten digit classifier using the MNIST dataset and a Deep Neural Network (DNN) built with TensorFlow and Keras. The model is trained using the Sequential API and evaluated with multiple classification metrics.

📂 Dataset: MNIST

MNIST (Modified National Institute of Standards and Technology) is a dataset of 70,000 grayscale images (28x28 pixels) of handwritten digits (0-9).

It is split into 60,000 training images and 10,000 test images.

Each image corresponds to a label (digit from 0 to 9).

🏗️ Model Architecture

The model is a fully connected feedforward neural network with the following layers:

Flatten Layer: Converts the 2D image into a 1D vector.

Dense Layer (300 neurons, ReLU activation)

Dense Layer (100 neurons, ReLU activation)

Output Layer (10 neurons, Softmax activation): Outputs class probabilities for digits 0-9.

⚙️ Training and Optimization

Loss Function: Sparse Categorical Crossentropy

Optimizer: Stochastic Gradient Descent (SGD)

Metrics: Accuracy

Epochs: 30

📊 Evaluation Metrics

To assess the model's performance, the following metrics are used:

Accuracy: Measures the percentage of correct predictions.

Classification Report: Displays precision, recall, and F1-score for each class.

Confusion Matrix: Provides insight into misclassifications.

Log Loss: Evaluates prediction confidence.

🚀 How to Run the Code

Install dependencies:

pip install tensorflow numpy matplotlib pandas scikit-learn

Run the Jupyter Notebook or Google Colab file.

Train the model and evaluate its performance.

View the training history and metrics.
