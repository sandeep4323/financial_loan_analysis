# 📊 Bank Loan Analysis using Python

A comprehensive **Exploratory Data Analysis (EDA)** project on a real-world bank loan dataset. This project explores borrower demographics, loan characteristics, repayment behavior, and credit risk factors to generate meaningful business insights using Python.

---

# 📁 Dataset

The project uses the **financial_loan.xlsx** dataset containing **38,576 loan applications** with **24 features**.

### Loan Information
- Loan Amount
- Installment
- Interest Rate
- Loan Term
- Grade
- Sub Grade
- Loan Purpose

### Borrower Information
- Annual Income
- Employment Length
- Employment Title
- Debt-to-Income Ratio (DTI)
- Home Ownership
- Verification Status
- Address State

### Loan Outcome
- Fully Paid
- Current
- Charged Off

### Date Columns
- Issue Date
- Last Payment Date
- Next Payment Date
- Last Credit Pull Date

> **Note:** This dataset is based on LendingClub-style US loan data. All monetary values are represented in **USD ($).**

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

---

# 🧹 Data Cleaning

The following preprocessing steps were performed before analysis:

- Checked missing values
- Removed duplicate records
- Converted date columns into datetime format
- Filled missing values in **emp_title** using the mode within each **emp_length** group
- Verified data types
- Prepared the dataset for analysis and visualization

---

# 📊 Exploratory Data Analysis

The following analyses were performed:

## Distribution Analysis
- Loan Status Distribution
- Loan Grade Distribution
- Home Ownership Distribution
- Verification Status Distribution
- Loan Purpose Distribution

## Numerical Analysis
- Loan Amount Distribution
- Installment Distribution
- Annual Income Distribution
- Interest Rate Distribution
- Debt-to-Income Ratio Distribution

## Relationship Analysis
- Loan Amount vs Annual Income (Scatter Plot)
- Loan Amount by Grade (Box Plot)
- Interest Rate vs Loan Status
- Debt-to-Income Ratio vs Loan Status
- Monthly Loan Application Trend
- Grade vs Loan Status
- Home Ownership vs Loan Status
- Verification Status vs Loan Status
- Loan Term vs Loan Status

## Correlation Analysis
- Correlation Heatmap of Numerical Features

## Regional Analysis
- Top 10 States by Loan Applications

## Summary Analysis
- Business Insights
- Risk Segmentation

---

# 📈 Visualizations Used

- 📊 Bar Chart
- 📈 Line Chart
- 🥧 Pie Chart
- 🍩 Donut Chart
- 📉 Histogram
- 🔵 Scatter Plot
- 📦 Box Plot
- 🔥 Heatmap
- 📊 Count Plot
- 📋 Pivot Table

---

# 🔑 Key Insights

### 📌 Debt Consolidation
Debt Consolidation is the most common reason customers apply for loans.

### 📌 Borrower Income
Most applicants earn an annual income below **$100,000**, indicating that the majority of borrowers belong to low- and middle-income groups.

### 📌 Monthly Trend
December records the highest number of loan applications.

### 📌 Credit Grade
Borrowers with **Grade A** and **Grade B** demonstrate the strongest repayment performance and the lowest default risk.

### 📌 Loan Term
Loans with a **36-month** term generally perform better than **60-month** loans in terms of repayment.

### 📌 Home Ownership
Applicants with **Mortgage** and **Own** home ownership generally exhibit better repayment behavior than other categories.

### 📌 Correlation
Loan Amount, Installment, and Total Payment are strongly positively correlated.

Interest Rate has only a weak correlation with individual numerical variables, suggesting that pricing depends more on borrower credit quality than income alone.

---

# 📌 Project Highlights

- ✔ Data Cleaning
- ✔ Exploratory Data Analysis (EDA)
- ✔ Statistical Summary
- ✔ Data Visualization
- ✔ Correlation Analysis
- ✔ Financial Risk Analysis
- ✔ Business Insights
- ✔ Python Programming
- ✔ Pandas Data Analysis

---






# 📌 Conclusion

This project demonstrates practical data analysis skills using **Python, Pandas, NumPy, Matplotlib, and Seaborn** to analyze real-world financial loan data. It provides meaningful business insights into borrower behavior, repayment trends, credit risk, and loan performance, making it a strong portfolio project for aspiring Data Analysts.

---

# 👨‍💻 Author

## **Sandeep Dass**

**Aspiring Data Analyst**

### Skills
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Excel
- Power BI



⭐ **If you found this project helpful, consider giving this repository a Star!**
