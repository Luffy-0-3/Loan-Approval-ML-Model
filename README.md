# Loan-Approval-ML-Model

A machine learning project that predicts loan approval status using Support Vector Machine (SVM) classification based on applicant financial and demographic information.​

Overview
This project analyzes loan application data to build a predictive model that determines whether a loan application will be approved or rejected. The model uses various applicant features including income, credit history, education, and property area to make predictions.​

Dataset Features
The dataset contains the following key features :​

Loan_ID: Unique identifier for each loan application

Gender: Applicant's gender (Male/Female)

Married: Marital status (Yes/No)

Dependents: Number of dependents (0, 1, 2, 3+)

Education: Education level (Graduate/Not Graduate)

Self_Employed: Employment type (Yes/No)

ApplicantIncome: Primary applicant's income

CoapplicantIncome: Co-applicant's income

LoanAmount: Loan amount requested (in thousands)

Loan_Amount_Term: Loan repayment period (in months)

Credit_History: Credit history meets guidelines (1.0/0.0)

Property_Area: Property location (Urban/Semiurban/Rural)

Loan_Status: Target variable (Y=Approved, N=Rejected)

Technologies Used
Python Libraries :​

NumPy for numerical operations

Pandas for data manipulation

Matplotlib and Seaborn for data visualization

Scikit-learn for machine learning implementation

Machine Learning Approach
Data Preprocessing
Missing value imputation using mean values for numerical features​

Label encoding for categorical variables​

Feature scaling and normalization​

Model Implementation
Algorithm: Support Vector Machine (SVM) with linear kernel​

Training Method: Train-test split for model validation​

Evaluation Metric: Accuracy score for performance measurement​

Key Statistics
The dataset contains 614 loan applications with the following characteristics :​

Average applicant income: ₹5,403

Average co-applicant income: ₹1,621

Average loan amount: ₹146,412

Most common loan term: 360 months

Credit history completion rate: 84.2%

Data Quality
Missing values were identified and handled in several features :​

Gender: 13 missing values

Dependents: 15 missing values

Self_Employed: 32 missing values

LoanAmount: 22 missing values

Credit_History: 50 missing values
