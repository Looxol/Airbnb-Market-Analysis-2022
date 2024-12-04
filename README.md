# Loan-Approval-Classification

## Project Overview
This project aims to develop a machine learning model to predict loan approval for educational purposes. 
The dataset used in this project is a synthetic version inspired by the Credit Risk dataset on Kaggle and enriched with additional financial risk factors. 
SMOTENC was employed to address class imbalance and generate synthetic data points.

---

## Project Description

### Data Description

**Numerical Features:**

* **person_age:** Age of the applicant (integer)
* **person_income:** Annual income of the applicant (float)
* **person_emp_exp:** Years of employment experience (integer)
* **loan_amnt:** Loan amount requested (integer)
* **loan_int_rate:** Loan interest rate (float)
* **loan_percent_income:** Percentage of annual income allocated to the loan (float)
* **cb_person_cred_hist_length:** Length of credit history in years (integer)
* **credit_score:** Credit score of the applicant (integer)
* **loan_status:** Loan approval status (0: Rejected, 1: Approved) (integer)

**Categorical Features:**

* **person_gender:** Gender of the applicant (categorical)
* **person_education:** Highest education level of the applicant (categorical)
* **person_home_ownership:** Home ownership status of the applicant (categorical)
* **loan_intent:** Purpose of the loan (categorical)
* **previous_loan_defaults_on_file:** Indicator of previous loan defaults (categorical)

