# Faster Credit Card Fraud Detection using Snap ML

## Project Overview

This project focuses on building a **Faster Credit Card Fraud Detection System** using **Snap ML** and **Support Vector Machine (SVM)**. The objective is to classify whether a credit card transaction is legitimate or fraudulent, leveraging the power of Snap ML to accelerate the machine learning process.

The dataset used contains transactions made by European cardholders in September 2013. The model achieves an impressive **accuracy of 96%** in detecting fraudulent transactions.

## Features

- **Machine Learning Algorithm:** Support Vector Machine (SVM)
- **Framework:** Snap ML (accelerated machine learning for faster model training and inference)
- **Accuracy:** 96%
- **Dataset:** [Credit card transaction dataset with legitimate and fraudulent transactions](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Preprocessing:** Feature scaling, imbalance handling, data splitting
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score, ROC-AUC
- **Tools/Libraries:**
  - Python
  - Snap ML
  - Scikit-learn
  - Pandas, NumPy for data manipulation

## Dataset

The dataset contains **transactions made by European credit cardholders** in September 2013. It includes:
- A total of **284,807 transactions**, with **492 fraudulent** transactions (highly imbalanced dataset).
- Each transaction has 30 features (anonymized) and a label indicating whether the transaction is **fraudulent** (1) or **legitimate** (0).

### Key Features:
- **V1 to V28:** Principal component analysis (PCA)-transformed features of the original data.
- **Time:** Number of seconds elapsed between the transaction and the first transaction in the dataset.
- **Amount:** Transaction amount.
- **Class:** Target label (0 for legitimate, 1 for fraud).

## Project Workflow

### 1. Data Preprocessing

Since the dataset is highly imbalanced and contains anonymized features, the preprocessing steps include:
- **Feature Scaling:** Use standardization or normalization to ensure features have comparable ranges.
- **Handling Imbalance:** Use techniques such as **undersampling**, **oversampling**, or **Synthetic Minority Over-sampling Technique (SMOTE)** to handle the imbalance.
- **Data Splitting:** Split the dataset into training (80%) and testing (20%) sets.
  
### 2. Model Training

- The **Support Vector Machine (SVM)** algorithm is chosen due to its robustness in handling classification problems, especially with imbalanced datasets.
- **Snap ML** is used to speed up training and inference, particularly beneficial for large datasets. Snap ML leverages hardware acceleration to enhance the efficiency of training machine learning models.
  
### 3. Model Evaluation

After training the model, it's important to assess its performance using various metrics:
- **Accuracy:** 96% accuracy achieved.
- **Precision, Recall, F1 Score:** These metrics are especially important for evaluating performance on imbalanced datasets.
- **ROC-AUC:** Evaluates the trade-off between true positive rate and false positive rate, providing a better measure for fraud detection.


<img width="718" alt="image" src="https://github.com/user-attachments/assets/8b68dab1-2f0f-4b56-829d-fe29fbe59e38">
