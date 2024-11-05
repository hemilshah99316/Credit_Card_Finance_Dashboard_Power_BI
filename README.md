# 💳 Credit Card Transaction Report Dashboard

## 📝 Project Overview

This project presents an in-depth analysis of credit card transactions using Power BI. The dashboard visualizes key financial metrics and offers insights into transaction patterns across various categories, customer demographics, and expenditure types.

### 📊 Data Sources

- **🗂 Customer Transactions Data**: Contains information such as transaction count, revenue, interest, transaction amounts, and usage patterns.
- **👥 Customer Demographics Data**: Provides customer attributes like age, education level, marital status, and occupation.

The data is stored in SQL Server, where any updates made to the data automatically refresh in Power BI, ensuring real-time data visualization.

### 🔄 Automated Data Flow

A data flow has been established between SQL Server and Power BI. This setup allows for **automatic data refresh** in the Power BI dashboard whenever new data is added to the SQL file, streamlining data updates and ensuring that the dashboard always reflects the latest information.

### ☁️ Power BI Service Publishing

The dashboard is published on **Power BI Service**, enabling online access and sharing of the visualizations. Stakeholders can view and interact with the dashboard from anywhere, making it a valuable tool for real-time decision-making.

### 🌟 Key Features

- **📈 Total Transaction Metrics**: Overview of transaction count, total revenue, total interest, and transaction amount.
- **🏫 Revenue by Customer Attributes**: Insights into revenue based on education level, occupation, and expenditure type.
- **📅 Transaction Trends**: Analysis of revenue and transaction volume by quarter, expenditure type, and card category.
- **💸 Customer Acquisition Cost**: Cost analysis by card category.
- **💳 Payment Method Analysis**: Revenue comparison between different payment methods (Swipe, Chip, Online).

### 📊 Visualizations

1. **Overview Cards**: Displays total metrics like transaction count, total revenue, and interest.
2. **🎓 Revenue by Education Level**: Highlights how customer education impacts revenue.
3. **💰 Revenue by Expenditure Type**: Shows top categories where customers spend the most.
4. **👔 Revenue by Occupation**: Analyzes how different job types contribute to total revenue.
5. **💳 Revenue by Payment Method**: Provides insights into payment preferences (Swipe, Chip, Online).
6. **🧮 Customer Acquisition Cost by Card Category**: Visualizes acquisition costs per card type.

### 💻 Technologies Used

- **💾 SQL Server**: Data storage and preprocessing.
- **📊 Power BI**: Data cleaning, transformation, and visualization.
- **☁️ Power BI Service**: Published online for easy access and sharing.

### ⚙️ How to Use

1. Clone this repository.
2. Open the Power BI file (.pbix) in Power BI Desktop.
3. Load data into Power BI if needed, ensuring paths to source files are correct.

### 🔍 Insights

- 🎓 **Graduates** contribute the highest revenue among education levels.
- 👔 **Businessmen and white-collar professionals** are top revenue generators by occupation.
- 🛒 **Bills and entertainment** are the top expenditure types among customers.
