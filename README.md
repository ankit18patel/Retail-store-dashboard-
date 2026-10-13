# Retail Store Sales Analysis & Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## 📌 Project Overview
This project focuses on cleaning raw retail store transaction data and building an interactive dashboard to uncover actionable business insights. The data was preprocessed and cleaned using Python (Pandas), and an executive-level dashboard was created using Power BI to visualize sales performance, customer behavior, and product trends.

![Dashboard Preview](https://github.com/ankit18patel/Retail-store-dashboard-/blob/main/dashboard%20img.png) 




## 🛠️ Tools & Technologies
*   **Data Cleaning & Preprocessing:** Python (Pandas)
*   **Data Visualization & Dashboarding:** Power BI
*   **Dataset:** `https://github.com/ankit18patel/Retail-store-dashboard-/blob/main/retail_store_sales_cleaned.csv`


## 🔄 Data Pipeline & Cleaning (Pandas)
The raw dataset underwent several cleaning steps in Pandas before being loaded into Power BI:
1.  **Handling Missing Values:** Imputed or dropped null values in key columns like `Discount Applied`, `Payment Method`, and `Category`.
2.  **Data Type Conversion:** Converted `Transaction Date` to datetime format and ensured numerical columns (`Price Per Unit`, `Quantity`, `Total Spent`) were formatted correctly.
3.  **Feature Engineering:** Created new derived columns (e.g., Month, Quarter, Year) to support time-series analysis.
4.  **Data Validation:** Removed duplicates and ensured that `Total Spent` = `Price Per Unit` * `Quantity` (accounting for discounts if applicable).
5.  **Export:** Saved the cleaned dataset as `https://github.com/ankit18patel/Retail-store-dashboard-/blob/main/retail_store_sales_cleaned.csv`.

## 📊 Dashboard Features (Power BI)
The interactive dashboard provides a comprehensive view of the retail store's performance:
*   **Key Performance Indicators (KPIs):** Total Quantity Sold (63K), Total Sales Revenue ($1.47M).
*   **Payment Method Analysis:** A pie chart showing the distribution of transactions across Cash, Credit Card, and Digital Wallet.
*   **Category Performance:** A pie chart showing the distribution of quantity sold across 8 major product categories.
*   **Revenue by Category:** A bar chart highlighting which categories generate the most revenue.
*   **Revenue by Location:** A comparison of total sales between In-store and Online channels.
*   **Monthly Sales Trends:** A detailed table breaking down Total Sales, Quantity Sold, and Average Price per unit by month.

## 📈 Key Insights
*   **Balanced Payment Methods:** Customer payment preferences are evenly distributed, with Digital Wallets leading slightly (34.47%), followed closely by Credit Cards (32.82%) and Cash (32.71%).
*   **Top Performing Category:** **Butchers** is the highest revenue-generating category, followed closely by Electric household essentials and Beverages.
*   **Lowest Performing Category:** **Patisserie** generates the least revenue among the categories, though its sales volume is comparable to others.
*   **Channel Performance:** Sales are almost evenly split between **In-store ($0.75M)** and **Online ($0.72M)** channels, indicating a strong omnichannel presence.
*   **Monthly Fluctuations:** While sales are relatively stable across the year, the dashboard table reveals that January is the highest revenue month ($165,611), while October is the lowest ($113,071).

