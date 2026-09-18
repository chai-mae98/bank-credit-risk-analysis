# Bank Credit Risk & Loan Portfolio dashboard
![screenshot](https://github.com/chai-mae98/bank-credit-risk-analysis/blob/main/dashboard.png)


# 📊Bank Credit Risk & Loan Portfolio Analysis-Project Documentation

## 📌 Project Overview
This project analyzes a bank loan portfolio to identify key factors associated with loan default risk. The analysis focuses on borrower characteristics, loan purpose, income burden, interest rates, home ownership, and previous default history.

The analysis was developed entirely in Microsoft Excel, using data cleaning, calculated fields, PivotTables, PivotCharts, slicers, and interactive dashboard techniques.

The objective is to transform raw loan-level data into a clear and structured financial analysis, helping identify risk patterns and portfolio segments associated with higher observed default rates.

## 🎯 Business Problem

Banks need to continuously monitor their loan portfolios to understand their **credit risk exposure** and identify borrower and loan segments associated with higher observed default rates.

The main business question addressed in this project is:

> **How can a bank analyze its loan portfolio to better understand credit risk and identify borrower and loan segments associated with higher observed default rates?**


## 🎯 Project Objectives

The main objectives of this analysis are to:

- Analyze the overall loan portfolio and its risk profile.
- Measure portfolio size, loan exposure, and key KPIs.
- Calculate the overall observed default rate.
- Analyze default rates across borrower and loan characteristics.
- Examine the relationship between income burden and observed default rates.
- Compare observed default rates across interest-rate categories.
- Analyze the role of previous default history in portfolio risk.
- Identify borrower and loan segments associated with higher observed default rates.
- Build an interactive **Excel dashboard** to communicate key findings.


## 📊 Dataset

The dataset contains information about borrowers, their loans, and their credit history.
- <a href="https://www.kaggle.com/datasets/urvishvekariya/credit-risk-assessment/data">Bank Credit Risk & Loan Portfolio</a>
### Main Variables

| Variable                     | Description                       |
| ---------------------------- | --------------------------------- |
| `person_age`                 | Borrower's age                    |
| `person_income`              | Borrower's annual income          |
| `person_home_ownership`      | Home ownership status             |
| `person_emp_length`          | Employment length                 |
| `loan_intent`                | Purpose of the loan               |
| `loan_amnt`                  | Loan amount                       |
| `loan_int_rate`              | Loan interest rate                |
| `loan_status`                | Loan default status               |
| `loan_percent_income`        | Loan amount relative to income    |
| `cb_person_default_on_file`  | Previous credit default indicator |
| `cb_person_cred_hist_length` | Length of credit history          |

In this dataset:

* `loan_status = 1` represents default.
* `loan_status = 0` represents non-default.

---

