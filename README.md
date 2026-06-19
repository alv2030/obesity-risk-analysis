# Obesity Risk Analysis

## Overview

This project analyzes obesity classification using demographic and education-related factors.

The objective is to explore how age group, gender, and education level relate to obesity risk and to evaluate logistic regression models for binary classification.

## Dataset

The dataset contains individual-level observations with categorical predictors including:

- Age group
- Gender
- Education level
- Obesity classification

A separate test dataset is used to evaluate model behavior on new observations.

## Objectives

- Explore obesity patterns across demographic groups
- Visualize relationships between categorical predictors and obesity status
- Build logistic regression models for obesity classification
- Evaluate classification performance using cross-validation and threshold-based error analysis
- Compare individual-level and aggregated binomial modeling approaches

## Methodology

### Exploratory Data Analysis

- Relabeled categorical variables for readability
- Created contingency tables
- Compared obesity proportions across age, gender, and education groups
- Used bar plots and mosaic plots to visualize categorical relationships

### Statistical Modeling

- Logistic Regression
- Cross-validated prediction probabilities
- Classification threshold analysis
- Aggregated Binomial Logistic Regression
- Complementary log-log link comparison

### Model Evaluation

- Likelihood ratio testing
- Goodness-of-fit testing
- Residual analysis
- Test-set classification error evaluation

## Technologies Used

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Skills Demonstrated

- Logistic Regression
- Binary Classification
- Statistical Modeling
- Cross-Validation
- Categorical Data Analysis
- Classification Threshold Evaluation
- Data Visualization
- Health Analytics

## Repository Files

- `obesity_risk_analysis.ipynb` — Main analysis notebook
- `obesity_data.txt` — Training dataset
- `obesity_test_data.txt` — Test dataset
- `requirements.txt` — Python dependencies
- `LICENSE` — MIT License

## Future Improvements

- Add ROC-AUC evaluation
- Add confusion matrix visualizations
- Compare with tree-based classification models
- Add feature importance and model explainability
