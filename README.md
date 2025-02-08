# Loan Approval Prediction

## Overview
This project predicts loan approval outcomes using machine learning techniques. By analyzing applicant details such as income, credit history, and loan amount, the model helps financial institutions assess risk and improve loan approval decisions.

## Project Workflow
1. **Data Collection & Cleaning**
   - Handled missing values in income, credit history, and loan term columns.
   - Applied encoding techniques to categorical variables.
   - Standardized numerical features for improved model performance.

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of key variables using **Plotly Express and Matplotlib**.
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
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly Express)
- **Machine Learning** (SVM, Model Evaluation Metrics)
- **Jupyter Notebook** (Project Development)

## How to Add This Project to GitHub from Jupyter Notebook
1. **Initialize a Git Repository** (Inside Jupyter Notebook or Terminal):
   ```bash
   git init
   ```
2. **Add the Project Files**:
   ```bash
   git add .
   ```
3. **Commit the Changes**:
   ```bash
   git commit -m "Initial commit - Loan Approval Prediction"
   ```
4. **Create a New GitHub Repository**
   - Go to [GitHub](https://github.com/) and create a new repository.
   - Copy the repository URL.

5. **Link Your Local Project to GitHub**:
   ```bash
   git remote add origin https://github.com/yourusername/loan-approval-prediction.git
   ```
6. **Push the Project to GitHub**:
   ```bash
   git branch -M main
   git push -u origin main
   ```

## Results & Findings
- **High approval prediction accuracy (83%)**, but low rejection recall.
- Identified key loan approval factors such as **credit history and applicant income**.
- Improved data quality by handling missing values and removing outliers.

## Next Steps
- Improve rejection recall through **class balancing techniques**.
- Deploy model as an **API using Flask/FastAPI**.
- Optimize feature selection and hyperparameters.
- Enhance visualization of insights using **advanced Matplotlib and Seaborn plots**.


