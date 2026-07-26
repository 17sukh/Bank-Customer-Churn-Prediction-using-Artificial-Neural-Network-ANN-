# Bank Customer Churn Prediction using Artificial Neural Network (ANN)

## 📌 Project Overview

This project predicts whether a bank customer is likely to leave (churn) within the next six months using an **Artificial Neural Network (ANN)**. The model is trained on customer demographic and financial information to perform binary classification and help banks identify customers at risk of leaving.

---

## 🎯 Objectives

- Read and preprocess the bank customer dataset
- Separate feature and target variables
- Split the dataset into training and testing sets
- Normalize the training and testing data
- Build and train an Artificial Neural Network (ANN)
- Improve the model by tuning network parameters
- Evaluate the model using Accuracy Score and Confusion Matrix

---

## 📂 Dataset

**Dataset:** Bank Customer Churn Modeling Dataset

https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

The dataset contains **10,000 customer records** with features such as:

- CustomerId
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumberOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (Target Variable)

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

---

## 📁 Project Structure

```
Bank-Customer-Churn-Prediction/
│
├── 3.ipynb
├── README.md
└──  Churn_Modelling.csv
```

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

- Loaded the dataset
- Removed unnecessary columns (CustomerId, Surname, RowNumber)
- Checked for missing values
- Encoded categorical variables (Gender, Geography)
- Prepared the dataset for model training

---

### 2. Feature and Target Selection

- Selected input features (X)
- Selected target variable (Exited)
- Divided the dataset into training and testing sets

---

### 3. Data Normalization

- Applied feature scaling using **StandardScaler**
- Normalized both training and testing datasets
- Improved convergence during neural network training

---

### 4. Artificial Neural Network (ANN)

The neural network consists of:

- Input Layer
- Hidden Layer(s) with ReLU activation
- Output Layer with Sigmoid activation

Model compiled using:

- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Metric:** Accuracy

---

### 5. Model Improvement

The model performance can be improved by:

- Increasing the number of hidden layers
- Adjusting the number of neurons
- Applying Dropout layers to reduce overfitting
- Increasing the number of epochs
- Hyperparameter tuning
- Early Stopping
- Batch Normalization

---

## 📊 Model Evaluation

The trained model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

---

## 📈 Results

| Evaluation Metric | Description |
|-------------------|-------------|
| Accuracy | Measures overall prediction correctness |
| Confusion Matrix | Displays correct and incorrect classifications |
| Precision | Measures positive prediction accuracy |
| Recall | Measures ability to detect churn customers |
| F1-Score | Harmonic mean of Precision and Recall |

The ANN model effectively predicts customer churn and can assist banks in identifying customers who are likely to leave.

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/Bank-Customer-Churn-Prediction.git
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
3.ipynb
```

Run all cells sequentially.

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow
keras
jupyter
```

---

## 📚 Deep Learning Pipeline

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Categorical Encoding
   │
   ▼
Feature Selection
   │
   ▼
Train-Test Split
   │
   ▼
Feature Scaling
   │
   ▼
Artificial Neural Network
   │
   ▼
Model Training
   │
   ▼
Prediction
   │
   ▼
Accuracy & Confusion Matrix
```

---

## 📌 Learning Outcomes

- Data preprocessing for deep learning
- Feature engineering
- Label encoding and one-hot encoding
- Feature scaling using StandardScaler
- Artificial Neural Networks (ANN)
- Binary Classification
- Model optimization techniques
- Accuracy evaluation
- Confusion Matrix analysis
- Customer Churn Prediction

---

## 👩‍💻 Author

**Sukhada Tamboli**

Interested in:

- Data Science
- Machine Learning
- Deep Learning
- Artificial Intelligence
- Python Development

---
