Project Overview
This project demonstrates how to use a Multilayer Perceptron (MLP) neural network for linear regression. Linear regression, typically achieved through statistical methods, is approached here with a neural network model. The project aims to explore the performance, flexibility, and limitations of MLPs when applied to regression tasks.


This project uses the following libraries:

TensorFlow/ Keras for constructing the MLP model
NumPy for data manipulation
pandas for dataset handling
Matplotlib for visualizations


Model Architecture
The model uses an MLP with:

Input layer - Corresponding to the number of input features in the dataset.
Hidden layers - A few dense layers with activation functions (e.g., ReLU).
Output layer - A single neuron for predicting a continuous value, using a linear activation function.

Model Configuration
Loss function: Mean Squared Error (MSE)
Optimizer: Adam
Evaluation metric: MSE or RMSE to assess prediction accuracy.

Results
The model's performance on the test set achieved an MSE of 0.10 for second order equation and 0.09 for third order equation
