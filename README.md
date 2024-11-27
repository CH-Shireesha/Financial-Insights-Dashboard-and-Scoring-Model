# Financial-Insights-Dashboard-and-Scoring-Model

#Overview
This project involves analyzing financial data to:
-->Identify spending patterns at family and member levels.
-->Develop a financial health scoring model.
-->Visualize key insights using Python libraries.

#Setup Instructions
-->Ensure the input data file "family_financial_and_transactions_data.xlsx" is located in the same directory as the notebook or the script.
-->Open the Jupyter Notebook file "Assignment.ipynb"

#Analysis
1. Spending Patterns Analysis
Family-Level Spending
Total Spending per Family:
-->This metric shows how much each family spends overall, aggregating all their transaction data.
-->Observing these totals helps identify high-spending families, which could indicate a need for better financial management.

Category-Wise Spending:
-->Spending is further broken down into categories (e.g., Travel, Groceries, Healthcare).
Insights:
-->Families with higher discretionary spending (Travel, Entertainment) may prioritize luxury over savings.
-->Families with higher essential spending (Healthcare, Education) may face unavoidable financial burdens.

Member-Level Spending
Average Spending per Member:
-->Identifies individual spending habits within a family.
-->This can reveal imbalances where certain members contribute disproportionately to expenses.

2. Financial Scoring Model
Family Financial Scores
Calculation:
Families were scored based on financial metrics such as:
-->Savings-to-Income Ratio.
-->Monthly Expenses as a Percentage of Income.
-->Loan Payments and Credit Card Spending.
-->Financial Goals Met.
-->Families with higher savings, controlled expenses, and fulfilled goals achieved better scores.
Insights:
-->Lower scores often resulted from high loan payments, excessive discretionary spending, or low savings-to-income ratios.

3. Correlation Analysis
Income vs. Monthly Expenses
Result: Weak negative correlation  (-0.041).
-->This suggests that income has little to no linear relationship with expenses in the dataset.
Possible reasons:
-->Families may have similar spending habits, irrespective of income.
Savings-to-Income Ratio vs. Monthly Expenses
Result: Weak negative correlation (-0.028).
-->Indicates that savings relative to income have minimal influence on monthly expenses.
-->High expenses could either coexist with high savings or occur despite low savings.

4. Visualizations
Family-Wise Financial Scores
--A bar plot showed scores across families.
Observation:
-->Families with lower scores often had high loan payments or excessive spending in discretionary categories.
-->Scores helped identify families in need of financial advice or intervention.

Spending Distribution Across Categories
-->A pie chart displayed spending proportions in categories like Groceries, Healthcare, Travel, etc.
Insights:
-->Families with high spending in discretionary categories (e.g., Travel, Entertainment) tended to have lower financial scores.
-->Essential spending categories (e.g., Healthcare, Education) dominated for families with average financial scores.

Scatter Plot: Savings-to-Income Ratio vs. Monthly Expenses
-->Visualized the weak relationship between savings and expenses.
Observation:
-->No clear trend, reinforcing the lack of a strong relationship between these variables.

