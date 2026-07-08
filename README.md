# Predictive Maintenance Using Machine Learning

## Overview

Predictive maintenance is a proactive maintenance strategy that uses machine learning to predict equipment failures before they occur. This project develops a predictive maintenance model using industrial sensor data to classify machine failures and compare the performance of multiple machine learning algorithms.

The project includes data preprocessing, exploratory data analysis, handling class imbalance using SMOTE, model training, hyperparameter tuning, and performance evaluation.

---

## Objectives

- Predict machine failures using industrial sensor data.
- Compare the performance of different machine learning classification algorithms.
- Improve prediction accuracy through preprocessing and hyperparameter tuning.
- Reduce unexpected equipment downtime by enabling predictive maintenance.

---

## Dataset

This project uses the **AI4I 2020 Predictive Maintenance Dataset**.

**Download the dataset here:**
- **UCI Machine Learning Repository:** https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset
- **Kaggle:** https://www.kaggle.com/datasets/shivamb/ai4i2020-predictive-maintenance-dataset

### Dataset Features

- UDI
- Product ID
- Type (L, M, H)
- Air Temperature [K]
- Process Temperature [K]
- Rotational Speed [rpm]
- Torque [Nm]
- Tool Wear [min]

### Target Variable

- Machine Failure
  - 0 → No Failure
  - 1 → Failure

Failure Types Included:
- Tool Wear Failure (TWF)
- Heat Dissipation Failure (HDF)
- Power Failure (PWF)
- Overstrain Failure (OSF)
- Random Failure (RNF)

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)

---

## Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)
- Random Forest Classifier

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Handling Class Imbalance using SMOTE
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Hyperparameter Tuning (GridSearchCV)
9. Model Evaluation
10. Performance Comparison

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score
- Classification Report

---

## Results

Among all the implemented models, the **Random Forest Classifier** achieved the best performance.

**Performance:**

- Accuracy: **96%**
- ROC-AUC Score: **0.964**

The Random Forest model outperformed the other classifiers by providing higher predictive accuracy and better overall classification performance.

---

## Future Scope

- Implement Gradient Boosting and XGBoost.
- Deploy the model using Flask or Streamlit.
- Integrate real-time IoT sensor data.
- Apply Explainable AI (SHAP/LIME) for model interpretation.
- Develop a real-time predictive maintenance dashboard.

---

## Author

**Shrawani Wagh**

B.Tech Electronics & Telecommunication Engineering

Interested in Machine Learning, VLSI, Embedded Systems, and Artificial Intelligence.
