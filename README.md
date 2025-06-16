# ANN – Diabetes Prediction

This project uses an Artificial Neural Network (ANN) to predict diabetes based on patient health data. It demonstrates how deep learning models can be used for binary classification tasks.

## Objective

To build a neural network that predicts whether a person is diabetic based on features like glucose level, BMI, insulin levels, and more.

## Dataset

The model uses a version of the PIMA Indians Diabetes dataset, a popular dataset for binary classification tasks.

## Steps Covered
- Data loading and preprocessing
- Feature scaling using StandardScaler
- Splitting data into training and test sets (80/20)
- ANN model design using Keras
- Training with validation monitoring
- Plotting accuracy and loss curves

## Libraries Used
- pandas, numpy
- scikit-learn
- tensorflow / keras
- matplotlib

## Model Architecture
- Input layer: 16 neurons, ReLU activation
- Hidden layer: 8 neurons, ReLU activation
- Output layer: 1 neuron, Sigmoid activation (binary classification)
- Dropout layer (0.3) for regularization

## Result
The model achieves ~75% validation accuracy, demonstrating solid predictive performance for a beginner-level ANN model.
