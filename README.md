# 💳 Credit Card Transaction & Customer Analytics Dashboard

## 📌 Project Overview

This project is an interactive **Credit Card Analytics Dashboard** built using **Microsoft Power BI**. It provides insights into credit card transactions, customer demographics, spending behavior, revenue generation, and financial performance.

The dashboard helps analyze transaction patterns, understand customer segments, and identify key business trends through interactive visualizations and KPIs.

## 🎯 Project Objectives

- Analyze overall credit card transaction performance.
- Understand customer spending behavior and preferences.
- Track revenue and interest earned.
- Identify customer segments based on demographics and income.
- Analyze transaction trends across quarters and weeks.
- Evaluate card category performance.
- Provide actionable insights to support data-driven business decisions.

## 📊 Dashboard Pages

### 1. Credit Card Transaction Report

This page focuses on transaction-level performance and financial insights.

**Key metrics and analysis:**
- Total Transaction Amount
- Total Transaction Volume
- Revenue
- Interest Earned
- Card Category Analysis
- Expense Type Analysis
- Transaction Trends by Quarter
- Transactions by Payment Method (Chip, Swipe, Online)
- Revenue by Customer Job
- Revenue by Education Level

### 2. Credit Card Customer Report

This page focuses on customer demographics, segmentation, and behavior.

**Key metrics and analysis:**
- Total Revenue
- Customer Income
- Interest Earned
- Customer Satisfaction Score
- Revenue Trends Over Time
- Customer Analysis by Gender
- Customer Segmentation by Age Group
- Customer Distribution by Education Level
- Customer Analysis by Marital Status
- Customer Distribution by Income Group
- Customer Job Analysis
- Geographic Analysis by State

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Dashboard development and data visualization
- **Power Query** – Data transformation and cleaning
- **DAX** – Calculated measures and business metrics
- **Data Modeling** – Connecting customer and transaction datasets

## 📂 Dataset Structure

The project uses two primary tables:

### Credit_Card
Contains transaction-related information, including:

- Client_Num
- Card_Category
- Total_Trans_Amt
- Total_Trans_Vol
- Interest_Earned
- Revenue
- Exp Type
- Use Chip
- Qtr
- Week_Start_Date

### Customer
Contains customer demographic and financial information, including:

- Client_Num
- Gender
- Education_Level
- Customer_Job
- Income
- IncomeGroup
- AgeGroup
- Marital_Status
- Dependent_Count
- Cust_Satisfaction_Score
- state_cd

## ⚙️ How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/credit-card-analytics-dashboard.git
   ```

2. Navigate to the project folder.

3. Open the `.pbix` file using **Microsoft Power BI Desktop**.

4. If prompted, configure the data source or refresh the dataset.

5. Explore the interactive dashboard using filters, slicers, and visualizations.

## 💡 Key Business Insights

This dashboard can help businesses:

- Understand which card categories contribute most to revenue.
- Identify customer groups with higher spending patterns.
- Monitor transaction volumes and financial performance.
- Analyze customer preferences across different transaction methods.
- Understand revenue distribution across occupations and demographics.
- Track customer satisfaction and identify potential improvement areas.

## 📸 Dashboard Preview

Add screenshots of your dashboard here.

```markdown
![Credit Card Transaction Report](images/transaction-report.png)

![Credit Card Customer Report](images/customer-report.png)
```

## 📁 Repository Structure

```text
credit-card-analytics-dashboard/
│
├── credit_card.pbix
├── images/
│   ├── transaction-report.png
│   └── customer-report.png
│
└── README.md
```

## 🚀 Future Improvements

- Add advanced customer segmentation.
- Implement predictive analytics for transaction trends.
- Develop customer lifetime value analysis.
- Add fraud detection and anomaly analysis.
- Enhance reporting with additional financial KPIs.

## 👨‍💻 Author

**Your Name**

If you found this project useful, consider giving the repository a ⭐ on GitHub!

---

*This project is developed for data analytics and business intelligence learning purposes using Microsoft Power BI.*
