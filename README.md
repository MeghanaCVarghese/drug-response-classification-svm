# 💊 Drug Response Classification using SVM

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-SVM-green)
![Healthcare](https://img.shields.io/badge/Domain-Healthcare-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project builds a **Support Vector Machine (SVM)** model to classify whether a patient responds positively to a drug.

The model helps in predicting:
- 0 → No Response  
- 1 → Positive Response  

---

## 🏥 Business Problem

Pharmaceutical companies spend huge resources on clinical trials, but:

- Not all patients respond to drugs
- Trials are expensive and time-consuming
- Ineffective drugs increase risk and cost

👉 Machine Learning helps **predict drug response early**, enabling:
- Faster trials
- Reduced cost
- Personalized medicine

---

## 🎯 Objective

To develop a classification model that predicts drug response using SVM and optimize its performance using different kernels and hyperparameters.

---

## 📂 Dataset Description

The dataset includes:
- Patient-related features
- Clinical measurements
- Drug response (Target Variable)

Target:
- **0 → No Response**
- **1 → Positive Response**

---

## 🔍 Exploratory Data Analysis (EDA)

- Dataset structure and summary
- Missing values and duplicates check
- Statistical analysis
- Feature distributions

---

## 📊 Data Visualization

- Histograms for feature distributions
- Boxplots for outlier detection
- Correlation heatmap
- Pairplot for feature relationships
- Class distribution plot

---

## 🧹 Data Preprocessing

- One-hot encoding for categorical variables
- Train-test split (80-20)
- Feature scaling using StandardScaler

---

## ⚙️ SVM Model Implementation

- Linear SVM model
- Trained using Scikit-learn
- Evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

---

## 🔧 Hyperparameter Tuning

Used GridSearchCV to optimize:
- Kernel (linear, polynomial, RBF)
- Regularization parameter (C)
- Gamma values

---

## 📈 Model Comparison

Compared performance of:
- Linear Kernel
- Polynomial Kernel
- RBF Kernel

---

## 📊 Results Visualization

- Confusion Matrix Heatmap
- Kernel Performance Comparison (Bar Plot)

---

## 💡 Key Insights

### ✅ Strengths of SVM
- Works well for high-dimensional data
- Handles non-linear relationships using kernels
- Robust with proper tuning

### ⚠️ Limitations
- Computationally expensive
- Sensitive to parameter tuning
- Requires feature scaling

---

## 🏥 Real-World Applications

- Clinical trial optimization
- Drug effectiveness prediction
- Personalized medicine
- Healthcare decision support systems

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## ▶️ How to Run

git clone https://github.com/your-username/drug-response-classification-svm.git

cd drug-response-classification-svm

pip install -r requirements.txt

Run jupyter notebook

---

## 🚀 Future Improvements

* Try advanced models (XGBoost, Neural Networks)
* Handle class imbalance (SMOTE)
Deploy as a web app (Streamlit)
Feature importance analysis

---

## 👩‍💻 Author

Meghana C Varghese
Data Scientist | Machine Learning Enthusiast

