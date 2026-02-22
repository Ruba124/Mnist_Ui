
Handwritten Digit Classifier (99% Accuracy CNN)

An interactive Deep Learning application that recognizes handwritten digits in real-time.

This project uses a Convolutional Neural Network (CNN) trained on the MNIST dataset and is deployed via a Gradio web interface.

🚀 FeaturesHigh Accuracy:

Achieves ~99.2% accuracy on the test set.

Real-time Prediction: Draw a number and get an instant prediction with probability scores.Robust Preprocessing: Includes a custom pipeline to handle image inversion and normalization for real-world user input.

🏗️ Architecture

The model is built using TensorFlow/Keras with a funnel-shaped CNN architecture

Input Layer:
Convolutional Layers: Two blocks of Conv2D and MaxPooling2D to extract spatial features like curves and edges
.Dense Layers: A 128-neuron hidden layer with ReLU activation and Dropout (0.5) to prevent overfitting
.Output Layer: 10 neurons with Softmax activation to provide digit probabilities.


📸 Model Performance (Screenshots)
<img width="1610" height="610" alt="image" src="https://github.com/user-attachments/assets/c8a343fa-61cb-4e38-9172-0ba2abb7ee3c" />
