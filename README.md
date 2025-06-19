# Predicting Loan Defaults with Machine Learning

This project aims to develop a Machine Learning model capable of predicting whether a personal loan will be repaid or defaulted, using real-world loan data.

## Objective

To anticipate credit risk by building a binary classification model (`paid = 1` / `default = 0`) that supports informed decision-making in financial institutions and reduces exposure to lending risk.

---

## Methodology

The pipeline follows all key stages of a standard machine learning project:

1. **Exploratory Data Analysis (EDA)**
   - Descriptive statistics
   - Visualization of variable distributions and correlations
   - Detection of outliers and key behavioral patterns
   - Generation of reports: `output_graphs.pdf` and `distribution_variables.pdf`

2. **Preprocessing**
   - Handling missing or inconsistent data
   - Removing outliers
   - Encoding categorical variables
   - Scaling numerical features for model optimization

3. **Class Imbalance Handling**
   - Application of **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the dataset by oversampling the minority class (`default`)

4. **Modeling**
   - Training and evaluation of multiple supervised classification algorithms:
     - Random Forest  
     - XGBoost  
     - HistGradientBoosting  
     - Logistic Regression

5. **Evaluation**
    - Performance metrics used:
    - Accuracy
    - Precision
    - Recall
    - F1-score
    - Confusion Matrix for error analysis

6. **Interpretability**
   - Feature importance analysis
   - Local and global explanation of model predictions using **SHAP**

---

## 📁 Repository Structure

    - Data.txt/ # Input data
    - Distribution in variables.pdf # EDA: distribution and analysis of variables
    - output_graphs.pdf # Plots and graphs from exploratory analysis
    - FINANCIAL_DEFAULT_PREDICTION.ipynb/  # Jupyter Notebook structured by each stage of the ML pipeline
    - Results.pdf/ # Model outputs, metrics, and reports
    - README.md # This fil
    - requirements.txt # List of Python dependencies

---
