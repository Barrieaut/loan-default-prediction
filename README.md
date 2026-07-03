# Loan Default Prediction and Fairness Analysis

This repository contains a machine learning workflow designed to predict financial loan defaults using the `bank-loan.csv` dataset. The project evaluates model performance alongside demographic fairness metrics.

## Repository Contents
* **loan_default_analysis.ipynb**: The primary Jupyter Notebook covering data cleaning, feature engineering, random forest modeling, and SHAP explainability.
* **ethical_considerations.pdf**: A formal report detailing fairness, privacy protection, and transparency strategies.

## Key Performance Results
* **Model Baseline Accuracy**: ~80%
* **Demographic Fairness**: Checked via calculated approval and selection rates stratified by gender.

## Technologies Used
* Python 3.x
* Pandas / NumPy / Scikit-Learn
* Matplotlib / Seaborn
* SHAP (SHapley Additive exPlanations)
