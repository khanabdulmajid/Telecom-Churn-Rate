# Customer Churn Prediction

## Overview
This project predicts customer churn for a telecom company. It uses machine learning models to identify customers likely to churn, helping businesses implement retention strategies.

## Features
- Exploratory data analysis (EDA) with visualizations.
- Preprocessing of categorical and numerical features.
- Handling class imbalance with SMOTE.
- Model building and evaluation (Logistic Regression, Random Forest, etc.).
- Precision, Recall, and F1-score analysis.

## Dataset
The dataset includes customer demographic and service details, such as:
- `gender`, `SeniorCitizen`, `tenure`
- `MonthlyCharges`, `TotalCharges`, etc.
Target column: **`Churn`** (Yes/No)

## Notebooks
1. **EDA.ipynb**: Insights and visualizations.
2. **Modeling.ipynb**: Building and evaluating machine learning models.

## Usage
1. Clone the repository:
   ```bash
   ## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/KhanAbdulMajid/Telecom-Churn-Rate.git
   cd Telecom-Churn-Rate

## Install dependencies:

pip install -r requirements.txt

##Run the scripts or notebooks:

    python src/preprocess.py
    python src/model.py

##Results

    Model Performance:
        Precision: 83%
        Recall: 51%
        F1-Score: 62%
    Visualizations: Link to plots

##Technologies

    Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
    Tools: Jupyter Notebook, Git

##Future Work

    Deploy model using Flask/Streamlit.
    Incorporate advanced models like XGBoost or Neural Networks.

