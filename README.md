# 🧠 Insurance Purchase Prediction using Neural Networks (Keras)

## 📌 Project Overview
This project is a **Binary Classification Model** built using **Keras (TensorFlow backend)** to predict whether a person will purchase insurance based on factors like **age** and **affordability**.

It demonstrates the implementation of a simple **Artificial Neural Network (ANN)** for solving a real-world classification problem.

---

## 🚀 Features
- Binary classification using Neural Networks
- Implemented with Keras Sequential API
- Uses sigmoid activation for prediction
- Data preprocessing with feature scaling
- Model training and evaluation

---

## 🛠️ Tech Stack
- Python 🐍
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn

---

## 📂 Dataset
The dataset contains:
- `age` → Age of the person
- `affordability` → Whether the person can afford insurance
- `bought_insurance` → Target variable (0 or 1)

---

## ⚙️ Model Architecture
- Input Layer: 2 neurons (age, affordability)
- Hidden Layer: (optional based on your code)
- Output Layer: 1 neuron with **sigmoid activation**

---

## 📉 Loss Function & Optimizer
- Loss Function: **Binary Crossentropy**
- Optimizer: **Adam**

---

## 📊 Training
- Data split using train-test split
- Model trained for multiple epochs
- Performance evaluated using accuracy and loss

---

## 🔍 How It Works
1. Load dataset
2. Perform preprocessing (scaling)
3. Split data into training and testing sets
4. Build neural network using Keras
5. Train the model
6. Predict output using trained model

---

## ▶️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/insurance-prediction-keras.git
cd insurance-prediction-keras
