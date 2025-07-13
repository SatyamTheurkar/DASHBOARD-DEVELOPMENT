# DASHBOARD-DEVELOPMENT

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : SATYAM THEURKAR

*INTERN ID* : CT06DF2424

*DOMAIN* : DATA ANALYTICS

*DURATION* : 6 WEEKS

*MENTOR* : NEELA SANTOSH

# Dashboard Development — Task 3

## Overview

This project is the third task in a series of internship-based assignments and focuses on **interactive dashboard development** using tools like **Tableau** and **Power BI**, with data preprocessing handled in **Google Colab**. The dataset used is the **Walmart Sales Dataset**, which was downloaded from **Kaggle**.

The primary objective is to create visually insightful dashboards that communicate key business metrics such as sales performance, store-level analysis, and operational patterns. This README summarizes the process from data acquisition to dashboard visualization in approximately 500 words.

---

## Dataset

The dataset contains historical sales records for multiple Walmart stores and departments, featuring:
- Store ID
- Weekly Sales
- Date
- Temperature
- Fuel Price
- Consumer Price Index (CPI)
- Unemployment Rate
- Holiday Flags

This rich dataset provides opportunities to explore various dimensions of Walmart’s retail operations over time.

---

## Tools & Platforms Used

- **Google Colab** for data cleaning and initial analysis.
- **Kaggle** for dataset sourcing.
- **Tableau / Power BI** for dashboard creation and data visualization.
- **Python (pandas, matplotlib)** for any initial data wrangling.

---

## Objectives

- Clean and preprocess Walmart data for dashboard use.
- Build dynamic and interactive dashboards to visualize key performance indicators (KPIs).
- Analyze seasonal trends, holiday impacts, and store-level performance.
- Enable stakeholders to make data-driven decisions via visual reports.

---

## Process Summary

### 1. Data Preprocessing (Google Colab)
The dataset was loaded in Colab and cleaned using `pandas`. Missing values were addressed, and data types were formatted appropriately. Unnecessary or null columns were dropped. This prepared the data for export into `.csv` format, which was used in Tableau/Power BI.

### 2. Dashboard Development
#### Tableau / Power BI
The cleaned dataset was imported into Tableau/Power BI, where different charts and visuals were developed to explore:
- Weekly sales trends
- Store-wise sales distribution
- Impact of holidays on revenue
- Correlation between temperature and sales
- Comparison of fuel price and consumer spending behavior

Slicers and filters were applied to make the dashboards interactive and user-friendly.

---

## Key Insights

- Holidays like Thanksgiving and Christmas showed significant spikes in sales.
- Some stores consistently outperformed others in weekly revenue.
- Temperature and fuel prices had subtle yet notable effects on consumer behavior.
- CPI and unemployment rate provided macroeconomic context to the retail trends.

---

## Outcome

The final dashboard provides Walmart decision-makers with an intuitive interface to monitor key sales metrics, identify problem areas, and make informed decisions. Visualizations simplify complex datasets and make them accessible even to non-technical users.

---

## How to Use

1. Clone or download this repository:
```bash
git clone https://github.com/yourusername/walmart-dashboard.git
```

2. Open the `.pbix` (Power BI) or `.twbx` (Tableau) file in the respective tool.

3. Use filters and slicers to interact with different metrics and timeframes.

---

## Author

**Satyam Theurkar**  
Task 3 – Internship Project  
Interactive Dashboard Development using Walmart Dataset

---

## License

This project is licensed under the MIT License.
