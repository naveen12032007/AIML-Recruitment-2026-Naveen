# AIML Recruitment 2026 - Naveen

## Task 2: Neural Network on MNIST

### Problem Statement

Build a neural network model to classify handwritten digits from the MNIST dataset. The model should recognize digits from 0 to 9 using image data.

## About MNIST

MNIST is a dataset of handwritten digit images.

- Image size: 28 × 28 pixels
- Number of classes: 10
- Classes: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- Training images: 60,000
- Testing images: 10,000

## Approach

1. Loaded the MNIST dataset using TensorFlow/Keras.
2. Normalized pixel values from 0–255 to 0–1.
3. Flattened each 28 × 28 image into a one-dimensional input.
4. Built a neural network with:
   - Input layer
   - Hidden layer with 128 neurons and ReLU activation
   - Output layer with 10 neurons and Softmax activation
5. Used Adam optimizer and sparse categorical cross-entropy loss.
6. Trained the model for 10 epochs.
7. Evaluated the model using the test dataset.
8. Generated training/validation accuracy and loss plots.
9. Generated a confusion matrix.
10. Performed an experiment by increasing the model size with two hidden layers.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- Jupyter Notebook

## Results

### Original Model

- Hidden layer: 128 neurons
- Test Accuracy: **97.63%**

### Experiment Model

- Hidden layers: 256 and 128 neurons
- Test Accuracy: **97.53%**

The experiment changed the neural network architecture by adding another hidden layer and increasing the number of neurons. The experiment model achieved a test accuracy of 97.53%, compared with 97.63% for the original model.

## Key Learnings

- Learned how to load and preprocess the MNIST dataset.
- Learned how neural networks classify images.
- Understood the use of ReLU and Softmax activation functions.
- Learned how to train and evaluate a neural network.
- Learned how to use confusion matrices to analyze classification results.
- Learned how changing the model architecture can affect performance.

## Project Structure

```text
AIML-Recruitment-2026-Naveen/
│
└── task2_mnist/
    └── mnist_neural_network.ipynb
