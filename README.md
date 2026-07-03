# 💳 UPI Transactions Analytics Dashboard using Power BI

An interactive **Business Intelligence Dashboard** built using **Microsoft Power BI** to analyze UPI transaction data across banks, customers, cities, merchants, payment methods, and transaction types. The dashboard provides actionable insights into transaction trends, account balances, and customer behavior through interactive visualizations.

---

# 📌 Project Overview

Unified Payments Interface (UPI) has transformed digital payments in India, generating millions of transactions every day. Analyzing this large volume of transaction data helps financial institutions understand customer behavior, monitor transaction trends, optimize banking operations, and support strategic decision-making.

This project demonstrates the complete Power BI workflow, including data cleaning, transformation, modeling, DAX calculations, and interactive dashboard development.

---

# 🎯 Business Objectives

- Analyze monthly UPI transaction trends
- Monitor account balance movements
- Compare transaction activity across banks
- Analyze customer demographics
- Evaluate merchant and payment method usage
- Enable interactive filtering and reporting
- Support business decision-making through visual analytics

---

# 📂 Dataset Information

The dataset contains UPI transaction details including:

### Customer Details

- Gender
- Age Group
- City

### Banking Details

- Bank Name (Sender)
- Bank Name (Receiver)

### Transaction Details

- Transaction Amount
- Remaining Balance
- Payment Method
- Transaction Type
- Merchant Name
- Purpose
- Device Type
- Month
- Year

---

# 🧹 Data Preparation

Data preprocessing was performed using **Power Query**.

### Data Cleaning

- Removed duplicate records
- Handled missing values
- Corrected data types
- Renamed columns
- Standardized categorical values
- Removed unnecessary fields
- Formatted currency values

### Data Transformation

- Created calculated columns
- Organized structured tables
- Prepared data for reporting
- Optimized data quality

---

# 🏗️ Data Modeling

Created relationships between multiple data tables to improve reporting performance.

Implemented:

- Fact Table
- Dimension Tables
- Star Schema
- Optimized Relationships

---

# 📊 Dashboard Features

## Interactive Filters

The dashboard provides dynamic filtering using slicers.

- Bank Name Sent
- Bank Name Received
- City
- Device Type
- Gender
- Age Group
- Merchant Name
- Payment Method
- Purpose
- Transaction Type

---

# 🚀 Interactive Dashboard Navigation

A key feature of this dashboard is the implementation of **Power BI Bookmarks** and **Navigation Buttons**.

Instead of creating multiple report pages, four interactive buttons dynamically switch between different visualizations on the same page.

### Dashboard Views

- 📈 Monthly Transactions (Line Chart)
- 📊 Monthly Transactions (Column Chart)
- 💰 Remaining Balance (Line Chart)
- 📉 Remaining Balance (Column Chart)

### Benefits

- Improved user experience
- Reduced dashboard clutter
- Faster navigation
- Better space utilization
- Interactive storytelling
- Professional dashboard design

---

# 📈 Dashboard Visualizations

### Monthly Transaction Trends

Analyzes transaction amounts across all months of 2024.

Provides insights into:

- Monthly transaction volume
- Peak transaction periods
- Seasonal trends

---

### Remaining Balance Analysis

Tracks monthly remaining balances after transactions.

Useful for:

- Financial monitoring
- Customer spending behavior
- Balance trend analysis

---

### City-wise Transaction Matrix

Displays transaction amount and remaining balance grouped by:

- City
- Currency
- Month

Supports geographical analysis and banking performance evaluation.

---

# 💡 Key Insights

- Monthly transaction volumes remain relatively stable throughout the year.
- Transaction amounts peak during May and October.
- Balance trends remain consistent with minor monthly variations.
- Interactive filters enable detailed customer and banking analysis.
- Bookmark navigation improves report usability by allowing users to switch between multiple chart types without changing pages.

---

# 🛠️ Power BI Features Used

## Power Query

- Data Cleaning
- Data Transformation
- Data Validation

## DAX

- Calculated Measures
- Aggregations
- Dynamic Calculations

## Interactive Features

- Bookmarks
- Navigation Buttons
- Slicers
- Drill-down
- Matrix Visualizations
- Conditional Formatting

---

# 💻 Technologies Used

| Tool | Purpose |
|------|----------|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Business Calculations |
| Microsoft Excel | Data Source |
| Data Modeling | Relationship Management |

---

# 📚 Skills Demonstrated

### Technical Skills

- Power BI
- Power Query
- DAX
- Data Modeling
- Dashboard Design
- Data Cleaning
- Data Transformation
- Interactive Reporting

### Analytical Skills

- Business Intelligence
- Financial Analytics
- Banking Analytics
- Trend Analysis
- Data Visualization
- KPI Reporting

---

# 📁 Repository Structure

```text
UPI-Transactions-Analytics-Dashboard/
│
├── Dashboard/
│   └── UPI_Transactions_Dashboard.pbix
│
├── Dataset/
│   └── UPI_Transactions.xlsx
│
├── Screenshots/
│   ├── Monthly_Transactions_Line.png
│   ├── Monthly_Transactions_Column.png
│   ├── Balance_Line_Chart.png
│   ├── Balance_Column_Chart.png
│   └── Transaction_Matrix.png
│
├── README.md
```

---

# 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/UPI-Transactions-Analytics-Dashboard.git
```

2. Open the `.pbix` file in **Microsoft Power BI Desktop**.

3. If required, reconnect the Excel dataset.

4. Refresh the data and explore the dashboard using interactive filters and navigation buttons.

---

# 🔮 Future Enhancements

- SQL Server Integration
- Real-time Data Refresh
- Power BI Service Deployment
- Power Automate Alerts
- Fraud Detection Dashboard
- Predictive Analytics
- Customer Segmentation
- Mobile Dashboard Optimization
- Row-Level Security (RLS)

---

# 👨‍💻 Author

**Vivekananda Survi**
