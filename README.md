# Loan Approval Prediction using SVM 🏦

## Overview
This project predicts the approval of loan applications using a **Support Vector Machine (SVM)** algorithm. The goal is to classify applicants as eligible or ineligible based on their financial and personal data.

---

## Features
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and standardizes numerical data.
- **Exploratory Data Analysis (EDA)**: Insights into features influencing loan approvals.
- **SVM Implementation**: Utilizes the SVM algorithm for classification.
- **Model Evaluation**: Includes metrics like accuracy, precision, recall, and F1-score.

---

## Dataset
The dataset should include the following columns:
- **ApplicantIncome**: Income of the applicant.
- **CoapplicantIncome**: Income of the co-applicant.
- **LoanAmount**: Loan amount requested.
- **Loan_Amount_Term**: Duration of the loan (in months).
- **Credit_History**: Credit history (1 for good, 0 for bad).
- **Gender, Married, Education, Self_Employed**: Applicant's personal details.
- **Loan_Status**: Target variable (Y for approved, N for not approved).

---

## Requirements
- **Python 3.x**
- Libraries:  
  - `NumPy`  
  - `Pandas`  
  - `Matplotlib`  
  - `Seaborn`  
  - `Scikit-learn`

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/loan-approval-svm.git
