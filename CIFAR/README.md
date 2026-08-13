# CIFAR-10 Image Classification using CNN

## 📌 Overview

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The model is trained to recognize 10 different object categories and achieves **86% accuracy on both training and test data**, demonstrating strong generalization performance.

CIFAR-10 consists of 60,000 32×32 color images divided into 10 classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## 🚀 Model Architecture

The CNN model includes:

- Multiple `Conv2D` layers with ReLU activation
- Batch Normalization layers
- MaxPooling layers for spatial downsampling
- Dropout for regularization
- Fully Connected (Dense) layers
- Softmax output layer for multi-class classification

Padding was configured appropriately to prevent dimensionality reduction issues during convolution.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Training Details

- Dataset: CIFAR-10 (from Keras datasets)
- Loss Function: Categorical / Sparse Categorical Crossentropy
- Optimizer: Adam
- Data Augmentation used for better generalization
- Epochs: Multiple training cycles to ensure convergence

---

## 📈 Results

- **Training Accuracy:** 86%
- **Test Accuracy:** 86%

The confusion matrix shows strong diagonal dominance, indicating accurate class predictions with minimal misclassification across categories.

---

## 🔍 Evaluation

Model performance was evaluated using:
- Accuracy metric
- Confusion Matrix visualization
- Training vs Validation accuracy comparison

The model demonstrates stable learning behavior with minimal overfitting.

---

## 📌 Key Learnings

- Importance of padding in convolution layers
- Impact of pooling layers on spatial dimensions
- Role of data augmentation in improving generalization
- Correct alignment between label encoding and loss functions
- Debugging common CNN dimensionality errors

---

## 📬 Conclusion

This project demonstrates effective implementation and tuning of a CNN for image classification. Achieving 86% accuracy on both training and testing datasets reflects balanced learning and good model generalization.

Further improvements could include:
- Deeper architectures
- Learning rate scheduling
- Transfer learning approaches
- Advanced regularization techniques
