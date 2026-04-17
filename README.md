# 🧠 Breast Cancer Classification with Neural Network
## 📌 Overview
This project implements a fully connected neural network **from scratch using NumPy** to classify breast cancer tumors as **benign** or **malignant**.
No high-level machine learning libraries such as TensorFlow, PyTorch, or scikit-learn were used. All core components — including forward propagation, backpropagation, loss computation, and gradient descent — are manually implemented.
## 🎯 Objective

The goal of this project is to build a neural network that predicts whether a tumor is:

- **Benign (0)**
- **Malignant (1)**

based on 30 numerical features extracted from cell nuclei.

---

## 🏗️ Model Architecture

The neural network has the following structure:
Input Layer: 30 features
Hidden Layer: 16 neurons (Sigmoid activation)
Output Layer: 1 neuron (Sigmoid activation)

⚙️ Implementation Details

#The model is built entirely from scratch using only:

numpy
pandas
matplotlib

# Key Components Implemented:
Data preprocessing (cleaning & normalization)
Train/Test split (80% / 20%)
Forward propagation
Sigmoid activation function
Binary Cross-Entropy loss
Backpropagation (chain rule)
Gradient Descent optimization

# 📊 Model Performance
Test Accuracy: ~96.5%
Loss decreases consistently during training
The model successfully distinguishes between benign and malignant tumors

# 📈 Visualizations
The project includes several visualizations to better understand the model:

📉 Loss curve (training progress)
🔲 Confusion matrix
📊 Data distribution plots
📈 Prediction vs actual visualization
🌡️ Weight matrices (heatmaps)
⚡ Hidden layer activations

# 🧪 Dataset
Name: Breast Cancer Wisconsin (Diagnostic)
Samples: 569
Features: 30 numerical features
Target: Diagnosis (Benign / Malignant)

🚀 How to Run

1. Download the dataset and place it as:
data.csv

2. Install required libraries (if not installed):
pip install numpy pandas matplotlib

3. Run the Python script:
python main.py

4. The model will:
Train on the dataset
Output performance metrics
Display visualizations

# 🧠 Key Learning Outcomes
This project demonstrates:
  How neural networks work internally
  How forward and backward propagation operate
  How gradients are computed manually
  How a model learns from data without using ML frameworks
