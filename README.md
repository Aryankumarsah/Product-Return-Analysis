# Product-Return-Analysis
This project analyzes product return data using Python (JupyterLab) for data cleaning and Power BI for interactive dashboard creation. It helps uncover key patterns by product name, return reason, brand, and region.

---

# Tools Used

- **Python (JupyterLab)** – Data cleaning & preprocessing
- **Power BI** – Dashboard and data visualization

---

## 📁 Project Structure
product-return-analysis/
│
├── data/
│ └── ecommerce_returns_data_cleaned.xlsx # Cleaned dataset
│
├── notebooks/
│ └── data_cleaning.ipynb # Jupyter Notebook (Python)
│
├── dashboard/
│ └── product_return_dashboard.pbix # Power BI dashboard
│
├── images/
│ └── dashboard-preview.png # Dashboard screenshot

---

## 📊 Features

- Cleaned and formatted raw product return data using Python (pandas)
- Removed missing/duplicate entries and standardized values
- Created an interactive dashboard in Power BI with:
  - Filters for Brand, City, Product Category, Return Reason
  - Charts: Clustered bar, Donut, Stacked bar, KPI indicators
- Identified high-return products, cities, and return reasons

---

## Dashboard Preview

![Dashboard Screenshot]("https://github.com/Aryankumarsah/Product-Return-Analysis/tree/main/images")

## Key Insights

- Most common return reason: **Damaged Item**
- High return categories: **Electronics**, **Clothing**
- Cities with highest returns: **Mumbai**, **Delhi**
- Top returned products identified for deeper analysis

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/product-return-analysis.git

2.Open the Jupyter notebook from /notebooks/ to view data cleaning steps

3.Open product_return_dashboard.pbix in Power BI to explore the dashboard

4.Use the cleaned Excel file for your own analysis if needed
