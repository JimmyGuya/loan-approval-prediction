# Loan Approval Prediction

## Overview
This project predicts loan approval outcomes using machine learning techniques. By analyzing applicant details such as income, credit history, and loan amount, the model helps financial institutions assess risk and improve loan approval decisions.

## Project Workflow
1. **Data Collection & Cleaning**
   - Handled missing values in loan amount, credit history, loan term and other categorical columns.
   - Applied encoding techniques to categorical variables.
   - Standardized numerical features for improved model performance.

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of key variables using **Plotly Express**.
   - Identified correlations between features and loan approval status.
   - Removed outliers using **Interquartile Range (IQR) method**.

3. **Model Training & Evaluation**
   - Used **Support Vector Machine (SVM)** as the primary classification model.
   - Evaluated performance using **accuracy, precision, recall, F1-score, and confusion matrix**.
   - Achieved an **83% accuracy rate** but noted bias toward approvals.

4. **Improvements & Future Work**
   - Address class imbalance using **SMOTE or weighted classification**.
   - Experiment with alternative models like **Random Forest or XGBoost**.
   - Adjust decision threshold to reduce false positives in loan approvals.
   - Deploy the model using **Flask or FastAPI** for real-world applications.

## Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Plotly Express)
- **Machine Learning** (SVM, Model Evaluation Metrics)
- **Jupyter Notebook** (Project Development)

## Results & Findings
- **High approval prediction accuracy (83%)**, but low rejection recall.
- Identified key loan approval factors such as **credit history and applicant income**.
- Improved data quality by handling missing values and removing outliers.

## Next Steps
- Improve rejection recall through **class balancing techniques**.
- Deploy model as an **API using Flask/FastAPI**.
- Optimize feature selection and hyperparameters.


