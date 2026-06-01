# Machine Learning Projects

This repository contains beginner-to-intermediate machine learning and deep learning projects implemented using Python, TensorFlow/Keras, and Scikit-learn. The projects focus on supervised learning, neural networks, regression modeling, data preprocessing, model evaluation, and visualization.

---

# Projects Included

## 1. MNIST Handwritten Digit Classifier using TensorFlow/Keras

A deep learning project that classifies handwritten digits (0–9) using a neural network trained on the MNIST dataset.

### Features
- Neural network implementation using TensorFlow/Keras
- Dense layers with ReLU activation
- Softmax multi-class classification
- Dropout regularization
- Data normalization and preprocessing
- Model training and evaluation
- Accuracy visualization

### Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

### Concepts Implemented
- Forward Propagation
- Backpropagation
- Activation Functions
- Optimization Algorithms
- Dropout Regularization
- Hyperparameter Tuning
- Deep Learning Workflow

### Dataset
MNIST Handwritten Digits Dataset  
https://keras.io/api/datasets/mnist/

### Typical Accuracy
- ~97% to 99%

---

## 2. Housing Price Prediction using Linear Regression

A machine learning regression project that predicts housing prices using the California Housing dataset.

### Features
- Linear Regression implementation using Scikit-learn
- Housing price prediction using multiple features
- Data preprocessing and train-test splitting
- Feature analysis and visualization
- Model evaluation using MSE and R² score
- Actual vs predicted value comparison

### Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

### Concepts Implemented
- Supervised Learning
- Linear Regression
- Gradient Descent Concepts
- Regression Metrics
- Data Visualization
- Feature Analysis
- Model Evaluation

### Dataset
California Housing Dataset  
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html

### Typical Performance
- R² Score: ~0.60 to 0.70

---

# Repository Structure

```bash
Machine-Learning-Projects/
│
├── MNIST_Digit_Classifier/
│   ├── mnist_digit_classifier.ipynb
│   ├── README.md
│
├── Housing_Price_Prediction/
│   ├── housing_price_prediction.ipynb
│   ├── README.md
│
└── README.md
```

---

# How to Run

## Option 1 — Google Colab
1. Open the notebook in Google Colab
2. Run all cells sequentially
3. Datasets download automatically

## Option 2 — Local Environment

Install required libraries:

```bash
pip install tensorflow scikit-learn pandas numpy matplotlib
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

# Learning Outcomes

These projects helped develop practical understanding of:

- Machine Learning Fundamentals
- Deep Learning Basics
- Neural Networks
- Regression Models
- Data Preprocessing
- Model Evaluation
- TensorFlow/Keras Workflow
- Scikit-learn Workflow
- Data Visualization

---

# Future Improvements

- Add Convolutional Neural Networks (CNNs)
- Implement advanced regression models
- Improve hyperparameter tuning
- Add feature scaling and engineering
- Deploy models using Flask or Streamlit

---

# Author

Aditya R Nair
