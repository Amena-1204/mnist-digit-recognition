# mnist-digit-recognition
A machine learning project that predicts handwritten digits using a CNN trained on the MNIST dataset.
This project is a machine learning model that predicts handwritten digits (0–9) using a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**.  
It takes an image of a handwritten digit and classifies it into one of ten categories with high accuracy.

# Features
- Built using **Python**, **TensorFlow/Keras**
- Uses the **MNIST dataset** for training and testing
- Achieves high accuracy in digit classification
- Can predict digits from custom images
- Includes visualization of model performance and predictions

# Technologies Used
- Python 🐍  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

# Dataset
The **MNIST dataset** contains 70,000 grayscale images of handwritten digits (0–9), each of size 28×28 pixels.

## 🧠 Model Architecture
- Input Layer (28x28)
- 2 Convolutional Layers
- 2 MaxPooling Layers
- Flatten Layer
- Dense Layer with ReLU activation
- Output Layer with Softmax (10 classes)

## ▶️ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/Amena-1204/mnist-digit-recognition.git
   cd mnist-digit-recognition
