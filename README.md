# HR Attrition ML Pipeline

## Project Overview
This project demonstrates an end-to-end Machine Learning pipeline for predicting employee attrition using Python. It focuses on how HR professionals can use data analytics and classification algorithms to identify potential employee resignations and support employee retention planning.

The project uses a synthetic dataset and is designed for educational purposes as part of learning Artificial Intelligence and Machine Learning in Human Resource Management.

## Business Problem
Employee attrition can create challenges for organisations, including recruitment costs, loss of talent, and workforce instability.

The objective of this project is to build a classification model that predicts whether an employee may resign within the following year, helping HR teams explore data-driven approaches to employee retention.

## Project Objectives
- Generate and analyse synthetic employee data.
- Clean missing values and duplicate records.
- Perform Exploratory Data Analysis (EDA).
- Select relevant features for attrition prediction.
- Handle class imbalance using SMOTENC.
- Train a Logistic Regression classification model.
- Evaluate model performance using classification metrics.
- Demonstrate predictions for a fictional employee.

## Dataset
The notebook automatically generates 1,000 fictional employee records and introduces 20 duplicate rows for data-cleaning practice.

**Key features include:**
- Department
- Work Mode
- Experience Years
- Monthly Salary
- Satisfaction Score
- Overtime Hours
- Absences

**Target variable:** `Resigned`
- `0` = Stayed
- `1` = Resigned within the following year

No real employee data is used.

## Machine Learning Workflow
1. Data generation and loading
2. Data inspection and quality checks
3. Data cleaning and duplicate removal
4. Feature selection and target identification
5. Training and testing split
6. Exploratory Data Analysis
7. Missing-value imputation
8. Numerical feature scaling
9. Class imbalance handling using SMOTENC
10. Categorical feature encoding
11. Logistic Regression model training
12. Model evaluation and comparison
13. Confusion matrix analysis
14. Prediction for a fictional employee
15. Saving the trained model and outputs

## Algorithms and Techniques
- **Logistic Regression:** Classification algorithm used to predict the attrition outcome.
- **SMOTENC:** Handles class imbalance in datasets containing numerical and categorical features.
- **StandardScaler:** Scales numerical features.
- **One-Hot Encoding:** Converts categorical variables into numerical representations.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn
- Joblib
- Google Colab
- Jupyter Notebook

## Model Evaluation
The project compares a baseline Logistic Regression model with a model trained using SMOTENC.

Evaluation metrics include:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual scores should be added after running the notebook. The purpose is to understand the trade-offs between detecting potential resignations and incorrectly flagging employees who stay.

## How to Run
1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run the setup cell to install the required libraries.
4. Execute the notebook cells from beginning to end.
5. Review the generated dataset, visualisations, model evaluation, and saved outputs.

The dataset is generated automatically; no external dataset download is required.

## Limitations
- The dataset is synthetic and may not reflect real organisational behaviour.
- Model performance does not establish real-world predictive effectiveness.
- SMOTENC generates synthetic training examples and does not guarantee better results.
- Predictions and feature associations do not establish the causes of attrition.
- Real-world implementation requires representative data, fairness checks, privacy safeguards, validation, and human oversight.

## Learning Outcomes
This project demonstrates practical knowledge of data preprocessing, feature selection, exploratory data analysis, classification, class imbalance handling, model evaluation, and HR analytics.

## Author
MBA HR Student | Artificial Intelligence and Machine Learning | HR Analytics

## Disclaimer
This is an educational project. Model predictions should not be used to make employment decisions about real employees.
