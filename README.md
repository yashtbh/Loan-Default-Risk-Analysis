# 💳 Loan Default Risk Analysis

## 📌 Project Overview
This project analyzes customer loan application data to uncover patterns in default behavior. Using Excel, we explored demographics, income, employment, education, and previous loan data to build insights that can help financial institutions reduce credit risk.

## 🎯 Objectives
- Clean and preprocess application data
- Handle missing values and outliers
- Explore demographic and financial patterns among defaulters
- Analyze previous loan behavior
- Identify key risk indicators for smarter loan approvals

## 🛠 Tools & Techniques
- Microsoft Excel 2019
- IQR method for outlier treatment
- Pivot tables and conditional formatting
- Correlation matrix analysis
- Charts: Histograms, bar charts, scatter plots

## 🧹 Data Cleaning
- Dropped columns with >40% missing data
- Filled missing numerics with median, categoricals with mode
- Applied IQR to cap outliers in credit, annuity, and income
- Treated anomalies (e.g., unrealistic employment days like 365,243)

## 📊 Key Findings
- 📉 Higher income = lower default risk
- 🧒 Age 27–35 showed highest default rates
- 💼 Longer employment duration reduces risk
- 🛠 Manual labor roles had higher default probability
- 🎓 Higher education = fewer defaults
- 💸 Cash loans are riskier than revolving loans
- 🔗 Strong correlation between credit amount & goods price (+0.97)

## 📊 Data Imbalance
- 91.95% non-defaulters, 8.05% defaulters
- Gender skew: 65.65% female applicants
- Most loans were short-term cash loans

## 🧠 Conclusion
Excel-based EDA revealed key behavioral and demographic insights linked to default risk. These can inform predictive models and help lenders implement better credit approval policies.


