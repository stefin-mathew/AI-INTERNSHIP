# Task 1 - Image Classification using Convolutional Neural Network (CNN)

## Project Overview

This project implements image classification on the CIFAR-10 dataset using Convolutional Neural Networks (CNN). Two different CNN models were developed and evaluated:

- Traditional CNN
- Customized CNN

The performance of both models was evaluated using standard classification metrics.

---

## Objective

The objective of this project is to build and compare CNN-based image classification models capable of accurately classifying images from the CIFAR-10 dataset into different categories.

---

## Dataset

**Dataset:** CIFAR-10

The dataset contains 60,000 color images of size 32×32 pixels belonging to 10 different classes.

Classes:
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

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Models Implemented

### 1. Traditional CNN

The traditional CNN consists of:

- Convolution Layers
- Max Pooling Layers
- Flatten Layer
- Dense Layers
- Softmax Output Layer

---

### 2. Customized CNN

The customized CNN includes:

- Additional Convolution Layers
- Batch Normalization
- Dropout Layers
- Data Augmentation
- Improved Architecture

---

## Performance Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

Example Traditional CNN Results:

- Accuracy: 69.38%
- Precision: 0.7018
- Recall: 0.6938
- F1 Score: 0.6906

---

## Project Files

```
Task1/
│── Task1.ipynb
│── README.md
│── requirements.txt
│── traditional_cnn.keras
│── customized_cnn.keras
│── accuracy.png
│── loss.png
│── confusion_matrix.png
```

---

## How to Run

1. Clone the repository.
2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```
Task1.ipynb
```

4. Run all cells from top to bottom.

---

## Conclusion

This project demonstrates the implementation of CNN models for image classification using the CIFAR-10 dataset. The customized CNN architecture was designed to improve performance over the traditional CNN by incorporating additional deep learning techniques such as batch normalization, dropout, and data augmentation.

---

## Author

**Stefin Mathew**

AI Internship Project – Task 1
