# SVR-delivery-time-prediction
# SVR with Linear Kernel — Predictive Modeling

This project applies **Support Vector Regression (SVR)** with a **linear kernel** to predict a continuous target variable.  
It includes **exploratory data analysis (EDA)** to visualize relationships, determine data linearity, and decide on the most suitable kernel.

## Features
- **EDA**: Scatter plots, correlation matrix to check data linearity before modeling.
- **Data Cleaning**: Handling NaN values and standardizing features.
- **Modeling**: SVR with a linear kernel.
- **Evaluation**: Mean Squared Error (MSE) and R² score.

## Workflow
1. **EDA** — Inspect linearity between features and target.
2. **Data Preprocessing** — Remove NaN rows, standardize data.
3. **Model Training** — Fit SVR with a linear kernel.
4. **Model Evaluation** — Report MSE and R².

## Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
