# Loan-Approval-Classification

## Project Overview
This project aims to develop a machine learning model to predict loan approval for educational purposes. 
The dataset used in this project is a synthetic version inspired by the Credit Risk dataset on Kaggle and enriched with additional financial risk factors. 
SMOTENC was employed to address class imbalance and generate synthetic data points.

---

## Project Description

### Data Description

* `person_age`: Age of the person (integer)
* `person_age`: Annual income (float)
* `person_emp_exp`: Years of employment experience (integer)
* `loan_amnt`: Loan amount requested (integer)
* `loan_int_rate`: Loan interest rate (float)
* `loan_percent_income`: Loan amount as a percentage of annual income (float)
* `cb_person_cred_hist_length`: Length of credit history in years (float)
* `credit_score`: Credit score of the person (integer)
* `loan_status` (target variable): Loan approval status: 1 = approved; 0 = rejected (integer)

**Categorical:**

* `person_gender`: Gender of the person (categorical)
* `person_education`: Highest education level (categorical)
* `person_home_ownership`: Home ownership status (categorical)
* `loan_intent`: Purpose of the loan (categorical)
* `previous_loan_defaults_on_file`: Indicator of previous loan defaults (categorical)
