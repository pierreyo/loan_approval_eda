# Loan Prediction EDA

# Overview

This project performs Exploratory Data Analysis (EDA) on a loan dataset. The dataset contains information about loan applicants, their financial status, and loan approval status. The objective of this analysis is to clean and preprocess the data, handle missing values, and gain insights from the available information.

# Dataset

The dataset contains the following columns:

Loan_ID: Unique identifier for each loan application

Gender: Applicant's gender (Male/Female)

Married: Marital status of the applicant

Dependents: Number of dependents of the applicant

Education: Education level (Graduate/Not Graduate)

Self_Employed: Whether the applicant is self-employed or not

ApplicantIncome: Applicant's income

CoapplicantIncome: Co-applicant's income

LoanAmount: Loan amount requested

Loan_Amount_Term: Term of loan in months

Credit_History: Credit history of the applicant

Property_Area: Type of property area (Urban, Semiurban, Rural)

Loan_Status: Whether the loan was approved or not

# Data Cleaning and Preprocessing

Handling Missing Values:

Missing values in Credit_History, Loan_Amount_Term, Self_Employed, Dependents, and Gender were filled using the mode.

LoanAmount missing values were filled using the mean.

Rows with more than 3 missing values were dropped.

Duplicate Removal:

No duplicate records were found in the dataset.

Outlier Treatment:

Extreme values in ApplicantIncome and CoapplicantIncome were identified but were not removed as they might be valid data points.

# Exploratory Data Analysis

Descriptive Statistics: Summary statistics were generated to understand the distribution of numerical variables.

Missing Values Analysis: A count of missing values per column was analyzed and imputed.

Loan Status Analysis: Distribution of approved and rejected loans was examined.

Income Analysis: Relationships between income levels and loan approvals were explored.

Credit History Impact: The effect of credit history on loan approval was analyzed.

Property Area Influence: Loan approvals across different property areas were compared.

# Libraries Used

numpy

pandas

matplotlib

seaborn
