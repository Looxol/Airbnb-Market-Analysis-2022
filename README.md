# Loan-Approval-Classification

## Project Overview
This project aims to develop a machine learning model to predict loan approval for educational purposes. 
The dataset used in this project is a synthetic version inspired by the Credit Risk dataset on Kaggle and enriched with additional financial risk factors. 
SMOTENC was employed to address class imbalance and generate synthetic data points.

---

## Project Description

### Data Description

### **Target Variable**
- **`loan_status`**: (Integer)
  - Loan approval status:
    - `1` = Approved
    - `0` = Rejected

### **Numerical Features**
- **`person_age`**: Age of the person (Float)
- **`person_income`**: Annual income (Float)
- **`person_emp_exp`**: Years of employment experience (Integer)
- **`loan_amnt`**: Loan amount requested (Float)
- **`loan_int_rate`**: Loan interest rate (Float)
- **`loan_percent_income`**: Loan amount as a percentage of annual income (Float)
- **`cb_person_cred_hist_length`**: Length of credit history in years (Float)
- **`credit_score`**: Credit score of the person (Integer)

### **Categorical Features**
- **`person_gender`**: Gender of the person
- **`person_education`**: Highest education level
- **`person_home_ownership`**: Home ownership status
- **`loan_intent`**: Purpose of the loan
- **`previous_loan_defaults_on_file`**: Indicator of previous loan defaults
