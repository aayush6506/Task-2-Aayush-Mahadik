# 💳 Online Payment Fraud Detection

A machine learning project for detecting potentially fraudulent online payment transactions using **Random Forest Classification**.

This project was developed as part of the **DecodeLabs Artificial Intelligence Internship**.

## 📌 Project Overview

Online payment systems process a large number of transactions, making automated fraud detection an important machine learning application.

This project uses transaction data to build a classification model that identifies whether a transaction is **fraudulent or legitimate**.

The project covers data loading, exploration, preprocessing, model training, and evaluation.

## 🎯 Objectives

* Analyze online payment transaction data
* Understand patterns associated with fraudulent transactions
* Prepare the dataset for machine learning
* Train a classification model
* Predict fraudulent transactions
* Evaluate the performance of the model

## 📊 Dataset

The project uses an online payment transaction dataset containing transaction information such as:

| Feature          | Description                                                 |
| ---------------- | ----------------------------------------------------------- |
| `step`           | Time step associated with the transaction                   |
| `type`           | Type of transaction                                         |
| `amount`         | Transaction amount                                          |
| `nameOrig`       | Originating customer identifier                             |
| `oldbalanceOrg`  | Original balance of the originating account                 |
| `newbalanceOrig` | Balance after the transaction                               |
| `nameDest`       | Destination customer identifier                             |
| `oldbalanceDest` | Original balance of the destination account                 |
| `newbalanceDest` | Balance after the transaction                               |
| `isFraud`        | Indicates whether the transaction is fraudulent             |
| `isFlaggedFraud` | Indicates whether the transaction was flagged as suspicious |

The dataset used in the notebook contains **198,843 rows and 11 columns**.

## 🔍 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Preparation
   ↓
Train-Test Split
   ↓
Random Forest Classifier
   ↓
Predictions
   ↓
Model Evaluation
```

## 🧠 Machine Learning Model

The project uses a:

### 🌲 Random Forest Classifier

Random Forest is a supervised machine learning classification algorithm that combines multiple decision trees to make predictions.

In this project, it is used to classify transactions based on the available transaction features.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Random Forest Classifier

## 📈 Model Evaluation

The trained model is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

These evaluation techniques help measure how effectively the model distinguishes between fraudulent and legitimate transactions.

## 📂 Project Structure

```text
Online-Payment-Fraud-Detection/
│
├── Online_Payment_Fraud_Detection.ipynb
└── README.md
```

## ▶️ How to Run

### Option 1 — Google Colab

1. Open `Online_Payment_Fraud_Detection.ipynb` in Google Colab.
2. Upload the dataset ZIP file when prompted.
3. Run the notebook cells sequentially.
4. The notebook will load and process the transaction data.
5. Train the Random Forest model.
6. View the evaluation results.

### Option 2 — Jupyter Notebook

1. Download the notebook.
2. Install the required Python libraries.
3. Open the notebook using Jupyter Notebook or JupyterLab.
4. Make sure the dataset is available at the expected location.
5. Run the cells sequentially.

## 📦 Installation

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🔐 Why Fraud Detection Matters

Fraudulent transactions can cause financial losses and affect the security and trust of online payment systems.

Machine learning can help identify suspicious transaction patterns and support automated fraud detection systems.

## 📚 What I Learned

Through this project, I learned:

* How to work with a real-world transaction dataset
* How to explore and understand financial transaction data
* How to prepare data for machine learning
* How classification models can be used for fraud detection
* How Random Forest works for classification
* How to evaluate a machine learning model
* How confusion matrices and classification reports can be used to analyze predictions

## 🚀 Future Improvements

Possible improvements include:

* Handling class imbalance using appropriate techniques
* Feature engineering for transaction behavior
* Comparing multiple machine learning algorithms
* Hyperparameter tuning
* Improving fraud detection performance
* Using additional evaluation metrics such as Precision, Recall, and F1-score
* Developing a real-time fraud detection system
