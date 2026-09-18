# Bank Credit Risk & Loan Portfolio Analysis
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


## 🧮 Analysis Methodology
The project followed a structured analytical process, from data preparation to dashboard development.

### 1. Data Preparation:

•	Reviewed the raw loan dataset

•	Checked the available variables and data structure 

•	Prepared the data for analysis

•	Created analytical categories where appropriate


### 2. KPI Calculation:

Calculated key portfolio indicators including:

•	Total number of loans

•	Total loan amount

•	Average Interest Rate  

•	Overall observed default rate

### 3. Risk Segmentation:

The loan portfolio was segmented according to:

•	Previous default history

•	Home ownership

•	Income burden

•	Interest-rate categories

These segments were used to compare observed default rates across different borrower and loan characteristics.

### 4. PivotTable Analysis:
PivotTables were used to:

• Calculate observed default rates.

• Compare portfolio segments.

• Analyze borrower and loan characteristics.

• Identify segments associated with higher observed default rates.


### 5. Dashboard Development:

The final Excel dashboard combines:

•	KPI cards

•	Risk analysis charts

•	Category comparisons

•	Interactive filters/slicers

•	Financial risk insights

---

## 📈 Key Portfolio KPIs

The dashboard contains **four major KPI cards** that provide a high-level overview of the analyzed loan portfolio.

### KPI 1 — Total Loans

**Dashboard Value: 32,409**

This KPI represents the **total number of loans** included in the analyzed portfolio.

**Purpose:** Provides an overview of the portfolio size and the number of loan records analyzed.

### KPI 2 — Total Loan Amount

**Dashboard Value: 310.9M**

This KPI represents the **total loan amount** across all loans included in the dataset.

**Purpose:** Measures the overall loan exposure represented by the analyzed portfolio.

### KPI 3 — Average Interest Rate

**Dashboard Value: 11.01%**

This KPI represents the **average interest rate** across the analyzed loans.

**Purpose:** Provides an overview of the average pricing level of the loan portfolio.

### KPI 4 — Overall Observed Default Rate

**Dashboard Value: 21.87%**

This KPI represents the **percentage of loans classified as defaulted** in the analyzed dataset.

**Purpose:** Provides a high-level indicator of the observed credit-risk profile of the portfolio.

---

# 📋 KPI Summary

| **KPI**                           | **Dashboard Value** | **Business Meaning**                        |
| --------------------------------- | ------------------: | ------------------------------------------- |
| **Total Loans**                   |          **32,409** | Total number of loans analyzed              |
| **Total Loan Amount**             |         **310.9M** | Total loan exposure in the portfolio        |
| **Average Interest Rate**         |          **11.01%** | Average interest rate across analyzed loans |
| **Overall Observed Default Rate** |          **21.87%** | Percentage of loans classified as defaulted |

> **Important:** These KPI values provide a high-level summary of the analyzed dataset. The observed default rate describes the proportion of loans classified as defaulted within this dataset and should not be interpreted as a standalone measure of future default probability.


## 🔎 Key Risk Insights

### 1. Previous Default History

Borrowers with a previous recorded default have a higher observed default rate than borrowers without a previous recorded default.

* **Previous Default:** 37.86%
* **No Previous Default:** 18.44%

This highlights the importance of **historical credit behavior** when analyzing and segmenting portfolio risk.

---

### 2. Home Ownership

Observed default rates vary substantially across home-ownership categories.

* **RENT:** 31.61%
* **OWN:** 7.49%

The difference indicates that home-ownership status is associated with different observed risk levels in this dataset and can therefore be useful for **portfolio segmentation and risk monitoring**.

---

### 3. Income Burden

Observed default rates increase significantly across the loan-to-income burden categories.

| Income Burden | Observed Default Rate |
| ------------- | --------------------: |
| Low           |            **13.56%** |
| Medium        |            **36.30%** |
| High          |            **73.97%** |
| Very High     |            **78.00%** |

The results show a strong association between **higher loan-to-income burden and higher observed default rates** in the analyzed dataset.

---

### 4. Interest Rate

Observed default rates also increase across the interest-rate categories.

| Interest Rate Category | Observed Default Rate |
| ---------------------- | --------------------: |
| Low                    |             **9.37%** |
| Medium                 |            **16.85%** |
| High                   |            **31.30%** |
| Very High              |            **63.30%** |

The results show a clear association between **higher interest-rate categories and higher observed default rates**.

However, this descriptive relationship should not be interpreted as evidence that higher interest rates directly cause default. Interest rates may also reflect **underlying borrower risk and other factors**.

> **Important:** These findings describe relationships observed in the dataset. They should not be interpreted as proof that any specific variable independently causes loan default.


# 🛠️ Tools & Skills

## 1.Tools:

### Microsoft Excel

Used for:

* Data cleaning and preparation
* Data analysis
* Excel formulas and calculated fields
* KPI calculations
* PivotTables
* PivotCharts
* Interactive dashboard development
* Slicers and filtering
* Financial and credit risk analysis

### PivotTables & PivotCharts

Used for:

* Portfolio segmentation
* Default rate analysis
* Comparing borrower characteristics
* Comparing loan characteristics
* Identifying risk patterns
* Creating analytical charts and visualizations

### Excel Slicers

Used for:

* Interactive filtering
* Portfolio exploration
* Segment-level analysis
* Dynamic dashboard navigation
* Exploring credit risk patterns across categories

### VBA

Used for:

* Supporting interactive slicer functionality
* Connecting dashboard elements and tables
* Improving dashboard usability

---

## 2. Skills Demonstrated
This project demonstrates the following **Data Analyst and Financial Analyst skills**:

* Microsoft Excel
* Data Cleaning & Preparation
* KPI Development
* Credit Risk Analysis
* Loan Portfolio Analysis
* Risk Segmentation
* Data Visualization
* Interactive Dashboard Development


# 📌 Portfolio/Resume Project Description

### **Bank Credit Risk & Loan Portfolio Analysis | Microsoft Excel**

> Developed an interactive **Microsoft Excel dashboard** to analyze a loan portfolio of **32,409 loan records**, focusing on portfolio exposure, interest rates, and observed credit risk. Created KPI calculations for **Total Loans, Total Loan Amount, Average Interest Rate, and Overall Observed Default Rate**. Analyzed observed default rates across previous default history, home ownership, income burden, and interest-rate categories using PivotTables, PivotCharts, slicers, and dashboard visualizations.

### Resume Bullet Points

* Developed an interactive **Excel Credit Risk & Loan Portfolio Dashboard** analyzing **32,409 loan records** and **$310.9M in total loan exposure**.
* Created portfolio KPIs including **Total Loans, Total Loan Amount, Average Interest Rate, and Overall Observed Default Rate**.
* Analyzed observed default rates across **previous default history, home ownership, income burden, and interest-rate categories**.
* Identified portfolio segments associated with higher observed default rates, including **Very High income burden (78.00%)**, **Very High interest-rate category (63.30%)**, and borrowers with **Previous Default history (37.86%)**.
* Applied **Excel formulas, PivotTables, PivotCharts, slicers, data analysis, and dashboard visualization techniques** to transform loan-level data into a structured financial risk analysis.

---

# 💡 Final Project Summary

**Bank Credit Risk & Loan Portfolio Analysis** is an Excel-based financial analytics project that transforms loan-level data into an interactive **credit risk and portfolio analysis dashboard**.

The dashboard provides a high-level view of **portfolio size, loan exposure, average interest rate, observed default rate, and risk patterns across different borrower and loan segments**.

The main dashboard KPIs are:

> 💰 **Total Loan Amount — 310.9M**
> 📋 **Total Loans — 32,409**
> 📈 **Average Interest Rate — 11.01%**
> ⚠️ **Overall Observed Default Rate — 21.87%**

Key observed risk patterns include:

* **Previous Default:** 37.86% observed default rate
* **No Previous Default:** 18.44%
* **RENT:** 31.61%
* **OWN:** 7.49%
* **Very High Income Burden:** 78.00%
* **Very High Interest-Rate Category:** 63.30%

> **Note:** These findings describe relationships observed within the analyzed dataset and should not be interpreted as proof that any individual factor independently causes loan default.

