# 🛒 Supermarket Sales Analysis

## 📌 Project Overview

This project analyzes 1,194 sales transactions recorded between March 2020 and March 2025 to evaluate sales performance, profitability, product and category performance, geographical trends, and customer payment behavior.

The project involved data cleaning and preparation, PivotTable analysis, data visualization, and the development of an interactive Excel dashboard.

## 🎯 Business Questions

The analysis aimed to answer:

- What were the overall sales and profit levels?
- Which products and categories generated the highest sales and profit?
- Which locations performed best in terms of sales and profitability?
- How did sales and profit performance change over time?
- Which payment methods were most commonly used by customers?

## 📂 Dataset

| Item | Details |
|---|---|
| Dataset | Sales Transaction Dataset |
| Records | 1,194 |
| Variables | 12 |
| Period | March 2020 – March 2025 |
| Tool | Microsoft Excel |

Key fields included Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode, Order Date, Customer Name, State, City, and Year-Month.

## 🧹 Data Cleaning & Preparation

The raw dataset was reviewed before analysis to identify inconsistencies and prepare the data for reporting.

Key cleaning activities included:

- Reviewing repeated Order IDs rather than automatically treating them as duplicates.
- Investigating Order ID inconsistencies alongside customer and transaction information.
- Standardizing relevant fields for analysis.
- Extracting Year and Month from Order Date for time-based analysis.
- Performing validation checks against the original dataset.

A separate cleaned dataset was created so that the original data could be preserved.

## 📊 Analytical Approach

The analysis was performed using Microsoft Excel.

The workflow was:

**Cleaned Dataset → PivotTables → Calculations & Metrics → Charts → Interactive Dashboard → Insights**

PivotTables were used to compare sales, profit, quantity, orders, categories, sub-categories, states, cities, payment methods, and time periods.

## 🔎 Key Findings

### Sales & Profitability

The dataset recorded:

- **Total Sales:** 6,182,639
- **Total Profit:** 1,610,697
- **Overall Profit Margin:** approximately 26.1%

2022 was the strongest complete year, generating approximately **1,459,775 in sales** and **393,113 in profit**.

### Product & Category Performance

**Office Supplies** was the highest-performing category by sales at approximately **2,089,510**.

At the sub-category level, **Markers** recorded the highest sales at approximately **627,875**.

### Geographic Performance

**New York** recorded the highest state-level sales at approximately **1,130,048**.

At city level, **Orlando** recorded the highest sales at approximately **452,158**.

### Payment Behavior

**Debit Card** was the leading payment method, generating approximately:

- **1,395,035 in sales**
- **375,721 in profit**

### Sales Trend

Sales increased from 2020 through 2022, reaching their highest point in 2022.

Sales subsequently declined in 2023 and 2024.

The 2025 figure should not be treated as a full-year result because the dataset only contains January–March 2025.

## 📈 Interactive Dashboard

The Excel dashboard allows users to interact with the analysis using:

- Category slicer
- Payment Mode slicer
- State slicer
- Year slicer
- Timeline

Users can apply filters and immediately observe how sales, profit, and other measures change.

## 💡 Business Recommendations

- Maintain adequate stock levels for high-performing product categories.
- Strengthen operations and promotional activities in high-performing locations.
- Investigate the decline in sales after 2022.
- Continue supporting debit-card payments while maintaining alternative payment options.

## ⚠️ Limitations

- 2025 contains only January–March data and therefore should not be compared directly with complete years.
- Repeated Order IDs were reviewed rather than automatically removed because one order may contain multiple items.
- The analysis identifies patterns but does not establish the causes behind those patterns.
- Year and Month fields were derived from the available Order Date information.

## 🛠️ Skills Demonstrated

- Microsoft Excel
- Data Cleaning
- Data Analysis
- PivotTables
- Data Visualization
- Dashboard Development
- Business Reporting
- Insight Generation

## 📁 Project Files

- `Sales Dataset(2).xlsx` — Complete Excel analysis workbook containing the dataset, cleaning, analysis, and dashboard.
- `Supermarket_Sales_Dashboard.png` — Preview of the interactive dashboard.
