# Fashion-MNIST CNN Classifier 👕👟

A Computer Vision project that classifies clothing images into 10 categories using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## 📌 Project Overview

This project uses the Fashion-MNIST dataset to train a deep learning model that recognizes different types of clothing from grayscale images.

## 🎯 Objectives

- Load and preprocess image data.
- Build and train a CNN model.
- Evaluate model performance on unseen test data.
- Visualize training results and a confusion matrix.
- Generate predictions for individual images.

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📊 Dataset

Fashion-MNIST contains 70,000 grayscale images across 10 clothing categories.

- Training images: 60,000
- Test images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10

## 🧠 Model Architecture

The CNN includes:

- Convolutional layers with ReLU activation
- Max Pooling layers
- Dropout for regularization
- Fully connected Dense layers
- Softmax output for 10-class classification

The model was trained using the Adam optimizer and sparse categorical cross-entropy loss.

## 📈 Results

**Test Accuracy: 91.02%**

The project also evaluates classification performance using a classification report and confusion matrix.

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries if they are not already available.
3. Run the notebook cells in order.
4. The Fashion-MNIST dataset will be downloaded automatically by TensorFlow.
5. Train the CNN and evaluate its performance.

## 📁 Project Structure

```text
fashion-mnist-cnn-classifier/
├── CV_project_.ipynb
├── README.md
└── .gitignore
```

## 📚 What I Learned

- Image preprocessing and normalization
- CNN architecture and image classification
- Model training and validation
- Performance evaluation and error analysis
- Making predictions with a trained deep learning model

---

*Built as a learning project in Computer Vision and Deep Learning.*
