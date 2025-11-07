💰 Financial Loan Data Analysis
📘 Project Overview

This project explores financial loan data to analyze lending trends, borrower behavior, and loan repayment performance.
Using Python and its data analysis libraries, this project performs data cleaning, exploratory data analysis (EDA), and visualization to identify insights that can help financial institutions make better credit and lending decisions.

📁 Dataset Information

File: financial_loan.csv

The dataset includes detailed information about loans and borrowers.
Key columns include:

🆔 id — Unique Loan ID

💸 loan_amount — Amount sanctioned to the borrower

💰 total_payment — Total amount repaid

📅 issue_date — Date when the loan was issued

📅 last_payment_date — Date of the last payment

📊 int_rate — Interest rate applied

📈 dti (Debt-to-Income ratio) — Borrower’s financial health indicator

🔄 loan_status — Indicates whether the loan is fully paid, charged off, or current

🎯 Objectives

Clean and preprocess loan data for analysis.

Explore borrower and loan characteristics to find key trends.

Analyze repayment patterns across different customer segments.

Visualize relationships between loan amount, interest rate, and default behavior.

Derive actionable insights for improving loan portfolio health.

⚙️ Tools & Libraries Used

Python

Pandas – Data cleaning and transformation

NumPy – Numerical computations

Matplotlib & Seaborn – Visualization and pattern analysis

Jupyter Notebook – Interactive data exploration

🧠 Analysis Summary

1. Data Cleaning

Handled missing values and formatted date columns (issue_date, last_payment_date).

Converted categorical values in loan_status for grouping and analysis.

2. Exploratory Data Analysis (EDA)

Distribution of loan amounts and interest rates.

Relationship between income levels and default probability.

Temporal trends — loan issues and repayments over time.

Segmentation of customers based on DTI and loan repayment status.

3. Key Metrics Computed

Average loan amount, total payment, and interest rate per loan type.

Default rate and recovery ratio by loan status.

Borrower risk profiles based on DTI and payment history.

📊 Key Insights

✅ Most loans are issued in mid-year months, showing peak seasonal demand.
✅ High-interest loans correlate with higher default risk, particularly for borrowers with DTI > 20%.
✅ Customers with consistent payments tend to have moderate loan amounts and lower interest rates.
✅ The “Charged Off” category shows a strong link with late payment dates and high DTI ratios.
✅ Banks can improve risk assessment by segmenting borrowers by DTI and interest rate thresholds.
