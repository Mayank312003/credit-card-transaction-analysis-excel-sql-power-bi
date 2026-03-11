# 💳 Credit Card Transaction Analysis

An end-to-end data analysis project focused on uncovering spending patterns, transaction trends, and key financial insights from credit card transaction data.
The project demonstrates the complete analytics workflow: data cleaning → data manipulation → business insights → interactive dashboard.

## 📌 Project Overview

Credit card transactions generate large amounts of financial data every day. Analyzing this data helps organizations understand:

- Customer spending behavior
- High value transaction segments
- Regional and category-based spending trends
- Revenue drivers and transaction performance
- This project analyzes credit card transaction data and builds an interactive Power BI dashboard to visualize important business insights.

## 🛠 Tools & Technologies Used
Tool	Purpose
Excel	Data Cleaning and Preprocessing
SQL	Data Querying and Manipulation
Power BI	Data Visualization & Dashboard Creation
DAX	Creating KPIs and Measures

## 🔄 Project Workflow
### 1️⃣ Data Cleaning (Excel)

- Raw transaction data was cleaned to ensure data quality.
- Tasks performed:
- Removed duplicates
- Handled missing values
- Standardized column formats
- Corrected inconsistent data entries
- Verified data types
- Result: Clean and structured dataset ready for analysis.

### 2️⃣ Data Manipulation (SQL)

SQL was used to explore and manipulate the dataset for deeper analysis.

Key SQL operations performed:
- Aggregation using SUM(), COUNT(), AVG()
- Grouping transactions by category, city, and card type
- Identifying top spending segments
- Transaction frequency analysis
- Filtering high-value transactions

### 3️⃣ Dashboard Creation (Power BI)

An interactive dashboard was built to visualize important metrics and trends.
Key visualizations include:
- Total Transactions
- Total Revenue Generated
- Spending by Card Type
- Spending by City
- Monthly Transaction Trends
- Category-wise Spending
- Interactive filters allow users to explore data dynamically.

## 📊 Key KPIs Created (Using DAX)

Custom measures were created in Power BI to track important performance indicators.
Examples:

- Total Transaction Amount

Total Transaction Amount = SUM(Transactions[transaction_amount])
Total Transactions
Total Transactions = COUNT(Transactions[transaction_id])

- Average Transaction Value

Average Transaction Value = 
DIVIDE([Total Transaction Amount], [Total Transactions])

## 📈 Key Insights

Some important insights derived from the analysis:
- Certain card types contribute significantly higher transaction volume.
- Spending patterns vary strongly across different cities.
- A few categories dominate overall spending behavior.
- Monthly transaction trends reveal peak spending periods.

These insights can help financial institutions improve customer targeting, fraud monitoring, and revenue strategies.

## 📷 Dashboard Preview

**Transaction Report:**

<img width="1457" height="838" alt="transaction_report" src="https://github.com/user-attachments/assets/1f6e73e4-332f-4fb5-ab1a-3798115e21dc" />


**Customer Report**

<img width="1458" height="843" alt="customer_report" src="https://github.com/user-attachments/assets/a2788762-124e-4f68-97fa-4b37aa253213" />


## 🚀 Business Value

This project demonstrates how transaction data can be used to:
- Identify high-value customers
- Monitor spending behavior
- Detect unusual transaction patterns
- Improve financial decision-making
- Support data-driven strategies

## 👨‍💻 Author

**Mayank Yadav**
**Aspiring Data Analyst | Machine Learning Enthusiast**

**Skills:**

- SQL
- Excel
- Power BI
- Python
- Machine Learning

**⭐ If you found this project useful, feel free to star the repository!**
