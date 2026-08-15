# Personal Finance Analytics Dashboard — Master Project Record

## Approved content
Executive Summary; Business Problem; Objectives & KPIs; Dataset & Data Preparation; Data Model; DAX & Analytical Layer; Dashboard Design & User Experience; Validation & Quality Assurance; Key Insights & Business Recommendations; Tools & Technologies; Conclusion & Project Outcome.

## Validated figures
- Total Income: $10,500
- Total Expenses: $5,528
- Net Cash Flow: $4,972
- Savings Rate: 47.35%
- Housing: $2,850 / 51.56%
- Food: $1,495 / 27.04%
- Housing + Food: 78.60%
- January Expenses: $1,860
- February Expenses: $1,835
- March Expenses: $1,833
- January-to-March expense change: -$27 / -1.45%
- January-to-March savings-rate improvement: +0.77 percentage points
- Monthly Income: $3,500

## Model
- `tblTransactions`
- `DimDate`
- `DimDate[Date]` 1 -> * `tblTransactions[Date]`
- DimDate fields: Date, Month Name, Month Number, Year, Year Month
- Month Name sorted by Month Number

## Power Query
Verified steps: Source, Navigation, Changed Type, Added Custom, Reordered Columns, Removed Columns, Changed Type1, Reordered Columns1, Renamed Columns.

## DAX measures
Total Income; Total Expenses; Net Cash Flow; Savings Rate; Average Income; Average Expense; Income Transactions; Expense Transactions.

## Status
Approved content consolidated for portfolio production.
