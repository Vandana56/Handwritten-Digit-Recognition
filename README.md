Handwritten Digit Recognition

Project Overview

Handwritten Digit Recognition is a machine learning project that identifies handwritten digits from 0 to 9 using a neural network. It uses the MNIST dataset and TensorFlow/Keras to train a model that classifies grayscale digit images.

Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- MNIST Dataset

Model Architecture

The project uses a Feedforward Neural Network (ANN) with the following layers:

1. Input: 28 × 28 grayscale image.
2. Flatten Layer: Converts the image into 784 numerical pixel values.
3. Hidden Layer: 128 neurons with ReLU activation.
4. Output Layer: 10 neurons with Softmax activation to predict digits from 0 to 9.

Workflow

1. Load the MNIST dataset.
2. Normalize pixel values between 0 and 1.
3. Build the neural network.
4. Train the model using the Adam optimizer.
5. Evaluate performance on test data.
6. Predict handwritten digits.

Installation

Install the required libraries:

pip install tensorflow numpy matplotlib

How to Run

1. Clone this repository.
2. Open the project in Google Colab or a local Python environment.
3. Run the Python script or notebook.
4. The model will train on the MNIST dataset and display a sample digit with its predicted label.

Results

The model typically achieves approximately 97–98% test accuracy after five training epochs. Actual results may vary.

Future Improvements

- Build a web interface using Streamlit.
- Allow users to upload their own handwritten digit images.
- Experiment with Convolutional Neural Networks (CNNs) for improved image recognition.

