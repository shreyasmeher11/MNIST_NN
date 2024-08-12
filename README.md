# MNIST_NN

# Custom Neural Network Framework

This repository contains a simple, customizable neural network framework built from scratch using Python. It includes implementations of common neural network layers, activation functions, a loss function, and an optimizer. The framework is designed to be easily extendable and can be trained on datasets like MNIST.

## Table of Contents

- [Usage](#usage)
  - [Loading Data](#loading-data)
  - [Creating a Model](#creating-a-model)
  - [Training the Model](#training-the-model)
  - [Evaluating the Model](#evaluating-the-model)
  - [Making Predictions](#making-predictions)
  - [Saving and Loading Models](#saving-and-loading-models)

## Usage

### Loading Data

- Load your dataset into a pandas DataFrame (e.g., `train.csv`, `test.csv`).

### Creating a Model

- Create a model by adding layers in the desired sequence using `add_layer` for each layer type (e.g., linear, relu, softmax).
- Compile the model to set the optimizer and loss function.

### Training the Model

- Prepare your training data by normalizing input data and one-hot encoding the labels.
- Train the model by specifying the number of epochs, batch size, and providing the training and test datasets.

### Evaluating the Model

- Evaluate the model's performance on the test dataset to calculate the loss.

### Making Predictions

- Generate predictions on new data using the trained model.

### Saving and Loading Models

- Save a trained model to a file for future use.
- Load a previously saved model to continue training or make predictions.

### Creating a Kaggle Submission

- Preprocess the `test.csv` file and predict the labels for the test data using the model.
- Format the predictions into a CSV file with the required `ImageId` and `Label` columns for submission to Kaggle.



