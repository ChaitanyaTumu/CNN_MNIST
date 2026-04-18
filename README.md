# Handwritten Digit Recognition using CNN on MNIST

## 🌟 Project Overview
This project demonstrates the implementation of a **Convolutional Neural Network (CNN)** using **TensorFlow** and **Keras** to classify handwritten digits (0-9) from the classic **MNIST dataset**. 

CNNs are highly effective for image classification tasks. This project walks through the entire pipeline: from loading and preprocessing the image data (reshaping and normalization), to encoding the target labels, building a multi-layer convolutional architecture, and finally training and evaluating the model.

## 🎯 Key Objectives
* Load and explore the MNIST handwritten digits dataset.
* Preprocess image data by reshaping it to include a channel dimension and normalizing pixel values.
* Apply One-Hot Encoding to categorical target labels.
* Build a CNN architecture utilizing `Conv2D`, `MaxPooling2D`, `Flatten`, and `Dense` layers.
* Compile and train the model using the `Adam` optimizer and `Categorical Crossentropy` loss.
* Evaluate the model's accuracy on unseen test data.

## 🛠️ Technology Stack
* **Python 3**
* **TensorFlow / Keras** (Deep Learning framework)
* **NumPy** (Data manipulation)

## 🧠 Model Architecture
1. **Convolutional Layer 1:** 32 filters of size (3x3), ReLU activation. Extracts low-level features.
2. **Max Pooling Layer 1:** Pool size (2x2). Reduces spatial dimensions.
3. **Convolutional Layer 2:** 64 filters of size (3x3), ReLU activation. Extracts higher-level features.
4. **Max Pooling Layer 2:** Pool size (2x2).
5. **Flatten Layer:** Converts 2D feature maps into a 1D vector.
6. **Dense Layer (Hidden):** 128 neurons, ReLU activation.
7. **Dense Layer (Output):** 10 neurons (one for each digit 0-9), Softmax activation to output probabilities.

## 🚀 How to Run
1. Clone this repository or download the `.ipynb` notebook.
2. Open the notebook in [Google Colab](https://colab.research.google.com/) or any local Jupyter environment.
3. Run all cells sequentially to observe data transformations, model construction, and training performance.
