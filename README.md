# Corporate Finance & Budget Performance Dashboard

## 📌 Project Overview
A financial performance dashboard designed for corporate CFOs and managers to track real-time spending and revenue against the allocated company budget for 2026. It highlights operational efficiency and budget variances across key corporate departments.

## 🛠️ Tech Stack & Skills
*   **BI Tool:** Power BI Desktop
*   **Data Source:** Corporate Financial Ledger (Excel)
*   **Languages:** DAX
*   **Key Concepts:** Budget vs. Actual Variance Analysis, Expense Categorization.

## 📈 Key Metrics & DAX Measures Used
1.  **Budget Variance:** `SUM(FinanceData[Actual_Amount]) - SUM(FinanceData[Budget_Amount])` - Identifies overspending or cost savings.
2.  **Budget Achievement %:** `DIVIDE(SUM(FinanceData[Actual_Amount]), SUM(FinanceData[Budget_Amount]), 0)` - Monitors the execution rate of the financial budget.

## 💡 Key Business Insights
*   Enables managers to instantly detect which departments (e.g., Marketing, Operations, Payroll) are exceeding their budgets.
*   The monthly slicer allows granular tracking of cash flow fluctuations per quarter.
# Corporate-Finance-Performance-Dashboard
