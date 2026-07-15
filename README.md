# E-commerce Sales & Customer Analytics Dashboard

An interactive **Business Intelligence dashboard** built with **Python** and **Streamlit** to analyze e-commerce sales performance and customer purchasing behavior.

This project transforms transactional data into **actionable business insights** through sales trend analysis, KPI monitoring, and **RFM (Recency, Frequency, Monetary)** customer segmentation. It is designed to help business stakeholders understand customer behavior, monitor performance, and support data-driven decision-making.

---

# Project Overview

Retail businesses generate thousands of customer transactions every day, making it difficult to identify purchasing patterns, monitor business performance, and understand customer value.

This dashboard addresses these challenges by providing an interactive analytics solution that enables users to:

- Monitor sales performance over time
- Track key business metrics
- Analyze customer purchasing behavior
- Identify high-value and at-risk customers
- Support marketing and retention strategies using RFM segmentation

---

# Project Objectives

- Analyze monthly sales trends and revenue performance.
- Monitor key business KPIs.
- Perform customer segmentation using RFM analysis.
- Identify valuable, loyal, and at-risk customers.
- Build an interactive dashboard for business users.
- Enable data-driven business decision making.

---

# Business Questions Addressed

- How does sales performance change over time?
- Which months generate the highest and lowest revenue?
- Which customers contribute the most business value?
- Which customer groups are at risk of churn?
- How can customer segmentation improve marketing strategies?

---

# Key Performance Indicators (KPIs)

The dashboard monitors important business metrics including:

- Total Revenue
- Total Orders
- Monthly Revenue
- Monthly Order Volume
- Customer Segments
- Average Recency
- Average Frequency
- Average Monetary Value
- Best Performing Month
- Lowest Performing Month

---

# Dashboard Features

## Sales Performance Analysis

- Monthly sales trends
- Revenue analysis
- Order volume analysis
- Best and worst performing months
- Time-based performance monitoring

## Customer Segmentation (RFM)

Customers are segmented using:

- **Recency** – How recently a customer placed an order
- **Frequency** – How often the customer purchases
- **Monetary** – Total customer spending

The dashboard helps identify:

- Loyal Customers
- High-Value Customers
- New Customers
- Potential Loyalists
- At-Risk Customers

## Interactive Dashboard

- User-friendly interface
- Time period filtering
- Interactive visualizations
- Business-focused KPI reporting

---

# Dataset

The project uses an e-commerce transactional dataset containing customer purchase information.

The preprocessing pipeline performs:

- Data cleaning
- Missing value handling
- Duplicate removal
- Date formatting
- Monthly sales aggregation
- Customer-level RFM calculation

To improve dashboard performance, only aggregated datasets are included in the repository.

---

# Methodology

The project follows the following analytics workflow:

```
Raw Transaction Data
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Monthly Sales Aggregation
        │
        ▼
RFM Analysis
        │
        ▼
Processed CSV Files
        │
        ▼
Interactive Streamlit Dashboard
```

---

# Business Insights

The dashboard enables businesses to:

- Monitor monthly sales performance.
- Identify seasonal revenue patterns.
- Discover high-value customer segments.
- Detect customers showing declining engagement.
- Improve customer retention strategies.
- Support targeted marketing campaigns.
- Enable faster business reporting.

---

# Business Recommendations

Based on the dashboard insights, businesses can:

- Reward loyal customers with exclusive offers.
- Re-engage at-risk customers through personalized campaigns.
- Improve customer retention initiatives.
- Monitor revenue fluctuations and seasonal trends.
- Develop targeted marketing strategies for different customer segments.

---

# Tech Stack

- Python
- Pandas
- NumPy
- Streamlit
- Matplotlib
- Streamlit Charts

---

# Skills Demonstrated

- Data Analysis
- Business Analytics
- Business Intelligence
- Dashboard Development
- Customer Analytics
- Sales Analytics
- KPI Monitoring
- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Customer Segmentation
- RFM Analysis
- Data Visualization
- Business Reporting
- Data-Driven Decision Making

---

# Project Structure

```
E-commerce-Sales-Customer/
│
├── dashboard.py              # Streamlit dashboard
├── preprocessing.py          # Data cleaning & preprocessing
├── requirements.txt
├── data/
│   ├── monthly_sales.csv
│   ├── rfm.csv
│
└── README.md
```

---

# Run Locally

```bash
git clone https://github.com/yourusername/E-commerce-Sales-Customer.git

cd E-commerce-Sales-Customer

pip install -r requirements.txt

streamlit run dashboard.py
```

---

# Notes

- The dashboard uses aggregated datasets for faster loading.
- Raw transactional data is excluded to keep the repository lightweight.
- RFM metrics are calculated during preprocessing for improved dashboard performance.
- The project is designed as a business analytics case study demonstrating dashboard development and customer segmentation techniques.

---

# Future Enhancements

Potential improvements include:

- SQL-based data pipeline
- Customer Lifetime Value (CLV) analysis
- Customer Retention Rate
- Repeat Purchase Rate
- Interactive KPI cards
- Month-over-Month (MoM) growth metrics
- Year-over-Year (YoY) analysis
- Sales forecasting using Machine Learning
- AI-generated business insights
- Natural language dashboard queries
- Real-time database integration
- Advanced Plotly visualizations


---

⭐ If you found this project helpful, consider giving it a star!
