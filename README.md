# Corporate Budget & Expense Intelligence Dashboard 📊💸

An advanced, executive-level Power BI Dashboard designed to track, monitor, and analyze financial performance, departmental expenses, and budget variances across a modern enterprise (Data tracking from January to May 2026).

## 🎯 Project Overview
In corporate financial planning, managing the gap between planned budgets and actual spending is critical. This project analyzes 100+ structural financial records across 6 major departments and expense categories to provide corporate stakeholders with actionable insights into cost-saving opportunities and budget overruns.

## 📊 Key Insights & Advanced Features Implemented
* **Core Financial KPIs:** Built optimized measures for **Total Budget**, **Total Actual Expense**, and **Budget Variance** using custom DAX expressions.
* **Smart Alert System (Conditional Formatting):** Implemented a dynamic 'Red-Green Alert' on the Budget Variance metric. It automatically highlights negative variances (overspending) in Red and positive variances (savings) in Green for instant executive review.
* **Departmental Variance Analysis:** Created a Clustered Column Chart to compare planned vs. actual spending, identifying which operational segments consistently breach their budget caps.
* **Expense Breakdown:** Developed a detailed Donut Chart mapping market share across multiple categories (Salaries, Marketing, IT, etc.) to isolate the heaviest cost drivers.
* **Timeline Trend Analysis:** Configured a Month-on-Month Line Chart using a categorical X-axis to visualize variance fluctuations over time, showcasing seasonal spikes in enterprise spending.

## 🛠️ Tech Stack & DAX Formulas Used
* **Data Source:** Structured Corporate Expense Dataset (Excel Workbook)
* **BI Tool:** Microsoft Power BI Desktop
* **Design Theme:** Premium Executive Corporate Palette
* **Key Measures Built:**
  * `Total Budget = SUM('Company Budger Data'[Budgeted_Amount])`
  * `Total Actual Expense = SUM('Company Budger Data'[Actual_Expense])`
  * `Budget Variance = [Total Budget] - [Total Actual Expense]`

---
*Developed as part of my Advanced Data Analytics Portfolio.*
