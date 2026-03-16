# 🤖 Neural Network & Machine Learning Assignments  
### 👨‍💻 By **Chakshu Gupta**

---

## 📘 Overview  
This repository contains my implementations of fundamental Machine Learning and Neural Network algorithms using **Python**, **NumPy**, and basic preprocessing tools.  
Each assignment focuses on building models **from scratch** to understand how the math and learning process actually work behind the scenes.

The assignments included are:

- 🟦 Perceptron for Logic Gates  
- 🟩 Logistic Regression  
- 🟨 Multiple Linear Regression  
- 🟪 Multilayer Perceptron (with Backpropagation)

All code is written in a simple and beginner-friendly manner so the core concepts stay clear.

---

# 🧠 Assignment 1 — Perceptron for Logic Gates  
### 🎯 Objective  
Implement a basic perceptron model and make it behave like common logic gates.

### 🔌 Logic Gates Implemented  
- AND  
- OR  
- NAND  
- NOR  

### 📄 Description  
A perceptron predicts output using:
y = f(w1x1 + w2x2 + b)


Where **f** is a step activation.  
By adjusting weights and bias, the perceptron can simulate the behavior of logical operations.  
This assignment helps understand how simple linear models can classify binary inputs.

### 🛠️ Technologies  
- Python  
- NumPy  

---

# 🧮 Assignment 2 — Logistic Regression (Single-Layer Perceptron)  
### 🎯 Objective  
Build logistic regression using a perceptron-style neural model and gradient descent.

### 📊 Dataset  
**Glass Identification Dataset**  
🔗 https://www.kaggle.com/datasets/uciml/glass

### 📄 Description  
The dataset contains chemical compositions for different glass types.  
A sigmoid function is used to map predictions between 0 and 1.

Workflow includes:

1. Data loading  
2. Normalizing features  
3. Training using gradient descent  
4. Predicting class labels  
5. Computing model accuracy  

### 🛠️ Technologies  
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

---

# 📊 Assignment 3 — Multiple Linear Regression  
### 🎯 Objective  
Implement a multiple linear regression model using a perceptron-like update rule.

### 📂 Dataset  
🔗 https://www.kaggle.com/datasets/hussainnasirkhan/multiple-linear-regression-dataset

### 📄 Description  
The goal is to predict a continuous output using multiple features.  
The prediction formula is:
y = w1x1 + w2x2 + ... + wn*xn + b


Weights are updated using gradient descent to minimize **Mean Squared Error (MSE)**.

### 🧵 Steps  
- Load dataset  
- Scale the input features  
- Train using gradient descent  
- Predict values on test data  
- Evaluate MSE  

### 🛠️ Technologies  
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

---

# 🤖 Assignment 4 — Multilayer Perceptron (MLP) with Backpropagation  
### 🎯 Objective  
Create a simple MLP network and train it using the backpropagation algorithm.

### 📂 Dataset  
**Abalone Dataset**  
🔗 https://archive.ics.uci.edu/dataset/1/abalone

### 📄 Description  
This dataset aims to predict the age of abalone from various physical attributes.  
The MLP used here includes:

- Input Layer  
- Hidden Layer  
- Output Layer  

Using **forward propagation**, predictions are generated.  
Using **backpropagation**, weights are adjusted to reduce the loss.

### 🧵 Workflow  
- Data cleaning & preprocessing  
- One-hot encoding (if required)  
- Forward pass  
- Loss computation  
- Backpropagation  
- Weight updates using gradient descent  

### 🛠️ Technologies  
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

---

# 📦 Requirements  
Install all required packages:

```bash
pip install numpy pandas scikit-learn
