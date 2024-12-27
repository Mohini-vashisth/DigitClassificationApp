
# MNIST Digit Classification with TensorFlow

This project demonstrates how to build and train a simple neural network using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

## Features
- **Data Preprocessing**: Normalization of input data and one-hot encoding of labels.
- **Neural Network**: A feedforward neural network with two hidden layers and a softmax output layer.
- **Training and Evaluation**: The model is trained with categorical crossentropy loss and Adam optimizer, and its performance is evaluated on the test dataset.

## Requirements
- Python 3.7+
- TensorFlow 2.x
- NumPy
- Matplotlib

## Installation
1. Clone the repository or download the script.
2. Install the required dependencies:
   ```bash
   pip install tensorflow numpy matplotlib
   ```

## Usage
1. Run the script:
   ```bash
   python mnist_classification.py
   ```
2. The script will:
   - Load and preprocess the MNIST dataset.
   - Train the neural network.
   - Evaluate the model's performance on the test dataset.
   - Display a sample prediction with the corresponding label.

## Model Architecture
- **Input Layer**: Flattens the 28x28 image into a 1D vector.
- **Hidden Layers**:
  - Dense layer with 128 units and ReLU activation.
  - Dense layer with 64 units and ReLU activation.
- **Output Layer**: Dense layer with 10 units and softmax activation for multi-class classification.

## Results
After training for 10 epochs, the model achieves a test accuracy of approximately 98% (subject to variation due to randomness in initialization).

## References
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- [TensorFlow Documentation](https://www.tensorflow.org/)


