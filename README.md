# Bankruptcy Prediction: A Machine Learning Approach

This repository contains the project for predicting bankruptcy using **machine learning** models, submitted for the **Machine Learning in Financial Engineering** course.

---

## Project Overview

The primary goal of this project is to leverage machine learning techniques to analyze financial data and predict company bankruptcy. The project explores data preprocessing, multiple machine learning models, and performance evaluations to identify the most effective prediction framework.

---

## Repository Structure

- **`Bankruptcy prediction.ipynb`**: The main Jupyter Notebook containing the entire workflow, including data preprocessing, model training, and evaluation.
- **`bankruptcy_helper.py`**: A helper script with reusable functions for data preprocessing, feature engineering, and visualization.
- **`Data.zip`**: Contains the dataset used for this project, including financial indicators for companies.

---

## Key Highlights

1. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Normalized and standardized features for better model performance.

2. **Feature Engineering**:
   - Created domain-specific financial ratios as features.
   - Applied feature selection techniques to retain the most predictive variables.

3. **Model Training**:
   - Trained multiple classification models（catboost, neural network...) to predict bankruptcy.
   - Used techniques like cross-validation to prevent overfitting.

4. **Model Evaluation**:
   - Plotted AUC-ROC curves to visualize model performance.
   - Compared metrics like precision, recall, and F1-score across different models.

---

## Results

- The best-performing model achieved:
  - **AUC-ROC**: 0.92
  - **Precision**: 0.89
  - **Recall**: 0.85
