# Handwritten Digit Recognition using Deep Learning

## Project Overview

This project focuses on recognizing handwritten digits using Deep Learning techniques on the MNIST dataset. The objective was to compare the performance of three neural network architectures:

- Perceptron
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)

The project demonstrates how model complexity impacts accuracy in image classification tasks.

---

## Problem Statement

Handwritten digit recognition is a fundamental Computer Vision problem with applications in:

- Postal code recognition
- Bank cheque processing
- Form digitization
- Automated data entry systems

The goal is to correctly classify handwritten digits (0–9) from grayscale images.

---

## Dataset

### MNIST Dataset

The MNIST dataset contains grayscale images of handwritten digits.

| Dataset | Images |
|----------|---------|
| Training Set | 60,000 |
| Testing Set | 10,000 |
| Image Size | 28 × 28 Pixels |
| Classes | 10 (Digits 0–9) |

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
- Loaded the MNIST dataset using TensorFlow/Keras.
- Split data into training and testing sets.

### 2. Data Preprocessing
- Normalized pixel values between 0 and 1.
- Reshaped images into 28×28×1 format.
- Applied One-Hot Encoding to labels.

### 3. Model Development

#### Perceptron
- Flatten Layer
- Dense Layer (Softmax)

#### Artificial Neural Network (ANN)
- Flatten Layer
- Dense (128, ReLU)
- Dense (64, ReLU)
- Dense (32, ReLU)
- Dense (10, Softmax)

#### Convolutional Neural Network (CNN)
- Conv2D (32 Filters)
- MaxPooling2D
- Conv2D (64 Filters)
- MaxPooling2D
- Flatten Layer
- Dense (128, ReLU)
- Dropout (0.5)
- Dense (10, Softmax)

### 4. Model Evaluation
- Accuracy Comparison
- Loss Analysis
- Confusion Matrix
- Prediction Testing
- Performance Visualization

  <img width="1774" height="517" alt="image" src="https://github.com/user-attachments/assets/b9cffdd6-ac01-42f8-b72c-e48671906b60" />


---

## Model Performance

| Model | Validation Accuracy |
|---------|---------|
| Perceptron | 89.66% |
| ANN | 96.95% |
| CNN | 98.69% |

### Best Performing Model

<img width="708" height="547" alt="image" src="https://github.com/user-attachments/assets/be70bff8-3fd1-483e-adb8-c32bb70ab16c" />


**CNN achieved the highest validation accuracy of 98.69%, outperforming both Perceptron and ANN models.**

---

## Results

### Perceptron
- Validation Accuracy: 89.66%
- Simple architecture with lower computational requirements.

### ANN
- Validation Accuracy: 96.95%
- Improved learning capability through multiple hidden layers.

### CNN
- Validation Accuracy: 98.69%
- Best performance due to automatic feature extraction and spatial pattern recognition.

  <img width="1490" height="345" alt="image" src="https://github.com/user-attachments/assets/299456f1-e0e7-4769-959f-8efbff4ad0f9" />


---

## Key Features

✅ Handwritten Digit Recognition

✅ Deep Learning Model Comparison

✅ Image Classification

✅ Training & Validation Performance Visualization

✅ Confusion Matrix Analysis

✅ Real-Time Prediction Testing

✅ CNN-Based Feature Extraction

---

## Key Learnings

- Deep Learning Fundamentals
- Neural Networks
- CNN Architecture
- Computer Vision
- Data Preprocessing
- Model Evaluation
- Hyperparameter Tuning
- Performance Comparison

---

## Future Enhancements

- Deploy using Streamlit
- Build a Web Application
- Allow User-Drawn Digit Input
- Train on Custom Handwritten Datasets
- Experiment with Advanced CNN Architectures

---

## Business Impact

This project demonstrates how Deep Learning can automate handwritten digit recognition, reducing manual effort and improving accuracy in document processing systems, banking applications, postal services, and OCR-based workflows.

---

## Author

**Jay Patil**

Aspiring AI/ML Engineer | Data Science & Artificial Intelligence Enthusiast

📧 Email: your-email@example.com

🔗 LinkedIn: https://www.linkedin.com/in/your-linkedin-profile

💻 GitHub: https://github.com/your-github-username

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
