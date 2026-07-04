# Saudi Tadawul Market Performance Analysis
<img width="2756" height="1484" alt="image" src="https://github.com/user-attachments/assets/1d7fe6af-0c4c-4a50-86f4-62413d450319" />

## 🚀 Project Overview
This project showcases the daily performance of Saudi Tadawul stocks during March and April 2020.The objective is to analyze market performance, identify high-liquidity and high-volatility stocks, and provide actionable insights for investment decisions.

## 📊 Project Highlights
**Data Scale:** Analyzed a high trading density reaching 3.64M trades with a total value of 77.09B SAR.
**Key Findings:**  The Information Technology sector was the highest-growing, reaching 86.38%.
    * Al Rajhi and Alinma were identified as liquidity leaders dominating trading value.
    * 67.38% of the days were "down" days, with Tuesday recording the highest drop percentage.

## 🛠 Tools Used
***Microsoft Excel:** Utilized for data processing via Power Query and analysis via Pivot Tables.

## ⚙️ Data Preparation & ETL
To ensure accuracy, the following steps were performed[cite: 51]:
**Data Cleaning:** Removed blank rows and redundant "Name" columns to reduce file size.
**Data Transformation:** Standardized data types (Decimal, Date, Text) and renamed columns for clarity.
**Validation:** Implemented a `check_perc_change` column to verify the integrity of the original data.
**Calculated Columns:** * **Trend:** Determined daily movement (Up/Down/No change) based on Open vs. Close prices.
    * **Volatility:** Calculated as `High - Low` to measure daily range.
    * **DayOfWeekName:** Extracted to analyze activity patterns.

## 📈 Dashboard Features
The interactive dashboard includes several visualizations:
**KPIs:** Total trades (3.64M), Total trading value (77.09B SAR), and peak daily volume (823.27M).
**Charts:** Closing Price vs. Trading Volume (Combo Chart).
    * Sector Performance Analysis (Donut Chart).
    * Top 5 Companies by Trading Value (Pie Chart).
    * Volatility and Activity Rankings (Bar Charts).
<img width="2490" height="1512" alt="image" src="https://github.com/user-attachments/assets/cfde9823-5ab9-45c2-a66e-da42605e21f4" />


## 🔗 Project Link
[View the full project on Behance](https://www.behance.net/gallery/247673089/Saudi-Tadawul-Market-Performance)
