* Financial Budget Tracking Dashboard

* Project Overview
The Financial Budget Tracking Dashboard is an interactive Excel-based dashboard designed to track and analyze income, expenses, and savings. It provides insights into financial health, spending patterns, and budget variance, helping users manage their finances effectively.

* Features
•	Automated Income & Expense Tracking
•	Dynamic Pivot Tables & Charts
•	Key Performance Indicators (KPIs)
•	Budget vs. Actual Expense Analysis
•	Slicers for Interactive Filtering

* Dataset Information
The dataset contains 1000 records with the following columns:
•	Month: Transaction month
•	Year: Transaction year
•	Income Source: Category of income (Salary, Freelance, Investments, etc.)
•	Income Amount: Amount received
•	Expense Category: Type of expense (Rent, Groceries, Transport, etc.)
•	Expense Amount: Amount spent
•	Budgeted Expense: Planned budget for the expense
•	Account Type: Payment method (Cash, Credit Card, Bank Transfer, Digital Wallet)

* Key Performance Indicators (KPIs) & Formulas
1.	Total Income: =SUM(B2:B1001)
2.	Total Expenses: =SUM(C2:C1001)
3.	Net Savings: =Total Income - Total Expenses
4.	Expense-to-Income Ratio (%): =(Total Expenses / Total Income) * 100
5.	Monthly Budget Variance (%): =((Actual Expenses - Budgeted Expenses) / Budgeted Expenses) * 100
6.	Expense Category Breakdown: =SUMIFS(C2:C1001, F2:F1001, "Rent")
7.	Savings Rate (%): =(Net Savings / Total Income) * 100

* Pivot Tables & Charts
Pivot Tables:
1.	Total Income & Expenses by Month
2.	Expense Breakdown by Category
3.	Income Source Contribution
4.	Budget vs. Actual Expenses
5.	Savings Rate Over Time
6.	Top 5 Expense Categories

* Charts:
1.	Income vs. Expenses (Clustered Column Chart)
2.	Expense Breakdown (Pie Chart)
3.	Monthly Savings Rate (Line Chart)
4.	Budget vs. Actual Expenses (Stacked Bar Chart)
5.	Expense Trends Over Time (Line Chart)

* Slicers for Interactivity:
•	Month & Year
•	Expense Category
•	Income Source
•	Account Type

* How to Use the Dashboard
1.	Download the dataset: Financial_Budget_Tracking.xlsx
2.	Open the file in Excel and go to the Dashboard sheet.
3.	Use slicers and filters to analyze financial trends.
4.	Check pivot tables and charts for income, expenses, and savings insights.
5.	Use the budget variance metric to identify overspending areas.

* Contribution
Feel free to contribute by improving the dataset, adding new KPIs, or optimizing Excel formulas.
