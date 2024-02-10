# Stroke Prediction Neural Network

## Overview

This code builds and trains a basic neural network for binary classification on the Stroke Prediction dataset. The dataset is preprocessed, features are normalized, and the model is trained using a custom-built neural network. The training loss is visualized, and the accuracy on the test set is reported as a measure of the model's performance.

## Prerequisites

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Installation

Ensure you have the required dependencies installed using:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage

1. Download the Stroke Prediction dataset (replace 'stroke_data.csv' with the actual file path).

2. Run the script to preprocess the data, train the neural network, and evaluate its performance.

```bash
python stroke_prediction_nn.py
```

## Code Structure

- **Data Loading and Preprocessing:**
  - The Stroke Prediction dataset is loaded, and missing values are handled.
  - Categorical variables are one-hot encoded, and features and labels are extracted.

- **Neural Network Definition:**
  - A custom neural network class is defined with methods for forward pass, backward pass, and training.
  - The network has an input layer, a hidden layer, and an output layer.

- **Training:**
  - The neural network is instantiated and trained using the training data.
  - Training loss is printed, and a plot of the training loss is displayed.

- **Testing and Evaluation:**
  - The trained model is tested on the test set, and predictions are compared to true labels.
  - The accuracy of the model is calculated and printed.

## Hyperparameters

- `hidden_size`: Number of neurons in the hidden layer (8).
- `epochs`: Number of training epochs (1000).
- `learning_rate`: Learning rate for updating weights and biases (0.01).

## Customization

- Adjust the hyperparameters to experiment with the model's performance.
- Modify the neural network architecture, learning rate, or other parameters as needed.

## License

This code is licensed under the [MIT License](LICENSE).

Feel free to customize and use this code for your binary classification tasks. If you find it helpful, consider providing attribution to the original source.