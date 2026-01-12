Bank Loan Performance Analysis (Python)
Project Overview

In this project, I performed an end-to-end exploratory data analysis on bank loan data using Python.
The objective was to evaluate loan performance, assess credit risk, and identify funding and repayment trends across different borrower and loan attributes.

This analysis focuses on key financial KPIs, loan health classification (Good vs Bad loans), and trend-based insights to support data-driven lending decisions.

Objectives

Analyze overall loan application volume and funding performance

Track Month-to-Date (MTD) loan activity

Classify loans into Good and Bad categories to assess portfolio risk

Identify trends across time, regions, loan purpose, employment length, and home ownership

Provide actionable insights into loan disbursement and repayment behavior

Dataset Overview

The dataset contains loan-level information including borrower details, loan characteristics, and repayment metrics.

Key Columns

id – Loan application identifier

issue_date – Loan issue date

loan_amount – Amount funded

total_payment – Amount received from borrower

int_rate – Interest rate

dti – Debt-to-Income ratio

loan_status – Loan repayment status

term – Loan tenure

emp_length – Employment length

purpose – Loan purpose

address_state – Borrower state

home_ownership – Home ownership status

Tools & Libraries Used

Python

Pandas – Data cleaning, transformation, and analysis

NumPy – Numerical computations

Matplotlib – Trend and distribution visualizations

Plotly – Interactive visualizations

Jupyter Notebook – Analysis workflow

Analysis Process
1. Data Cleaning & Preparation

Converted date columns to proper datetime format

Verified data types for numerical and categorical fields

Checked for missing values and inconsistencies

Standardized categorical values for accurate filtering and grouping

2. Key Performance Indicators (KPIs)

Overall KPIs

Total Loan Applications

Total Funded Amount

Total Amount Received

Average Interest Rate

Average Debt-to-Income (DTI) Ratio

Month-to-Date (MTD) KPIs

MTD Loan Applications

MTD Funded Amount

MTD Amount Received

MTD Average Interest Rate

3. Good Loan vs Bad Loan Analysis

Loans were classified based on loan status:

Good Loans: Fully Paid, Current

Bad Loans: Charged Off

Metrics Calculated

Good Loan Application Percentage

Good Loan Funded Amount

Good Loan Amount Received

Bad Loan Application Percentage

Bad Loan Funded Amount

Bad Loan Amount Received

This classification helps evaluate portfolio quality and credit risk exposure.

4. Exploratory Data Analysis (EDA)
Monthly Trends

Total Loan Applications by Month

Total Funded Amount by Month

Total Amount Received by Month

Used line and area charts to identify seasonality and long-term trends.

Regional Analysis

Total Funded Amount by State
Identified regions with higher lending activity and regional disparities.

Loan Term Analysis

Distribution of funded amount across different loan terms
Visualized using a donut chart.

Employment Length Analysis

Funded amount by borrower employment length
Assessed the impact of employment history on lending.

Loan Purpose Breakdown

Funded amount by loan purpose
Highlighted primary reasons borrowers seek loans.

Home Ownership Analysis

Total funded amount by home ownership category
Visualized using a treemap for hierarchical comparison.

Key Insights

Majority of loan funding and repayments come from Good Loans, indicating a relatively healthy portfolio

Clear seasonality observed in loan applications and funding trends

Certain states and loan purposes dominate overall loan disbursement

Employment length and home ownership show noticeable influence on funding distribution

Outcome

This project demonstrates a complete Python-based data analysis workflow, from raw data inspection to KPI computation and visual storytelling.
The insights derived can help financial institutions improve credit risk assessment, optimize lending strategies, and monitor portfolio performance effectively.
