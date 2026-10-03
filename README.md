# 🛒 E-Commerce Sales Analysis & Interactive Dashboard

An end-to-end data analysis and web application project for analyzing e-commerce transactions, understanding customer buying patterns, visualizing sales trends, and predicting purchase metrics.

--- 

## 📌 Project Overview

This repository contains an exploratory data analysis workflow and an interactive Streamlit dashboard (`ap.py`) designed to visualize e-commerce transaction data. The project cleans raw transactional logs, performs RFM (Recency, Frequency, Monetary) and trend analysis, and builds machine learning models to extract actionable business insights.

Key highlights:
- **Interactive Streamlit Web App**: Filter by date ranges and countries with real-time KPI metrics and Plotly/Matplotlib charts.
- **Exploratory Data Analysis (EDA)**: Jupyter Notebook (`Ecommerce_Analysis.ipynb`) detailing data preprocessing, outlier removal, feature engineering, and statistical modeling.
- **Machine Learning**: Linear regression models analyzing actual vs. predicted purchase values.
- **Visual Artifacts**: Saved chart visualizations showcasing top products, country-wise revenue, hourly/daily sales patterns, and correlation matrices.

---

## 🛠️ Tech Stack & Dependencies

- **Language**: Python 3.9+
- **Interactive Dashboard**: Streamlit
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Machine Learning**: Scikit-Learn
- **Notebook Environment**: Jupyter Notebook

---

## 📊 Features & Insights

1. **Executive Key Performance Indicators (KPIs)**:
   - Total Revenue (£)
   - Total Unique Orders
   - Total Active Customers
   - Average Order Value (AOV)

2. **Sales & Revenue Dynamics**:
   - Monthly and yearly revenue trend analysis.
   - Sales distribution across peak hours of the day and days of the week.
   - Revenue breakdown by geographic regions and top-performing countries.

3. **Product & Customer Analytics**:
   - Best-selling products by quantity sold and revenue generated.
   - Top high-value customer identification and customer segmentation metrics.
   - Correlation heatmap analyzing relationship between variables.

---

## 📂 Repository Structure

```
e_commerce-_analysis-_dashboards/
├── Ecommerce_Analysis.ipynb                   # Jupyter notebook with full EDA & ML models
├── ap.py                                      # Main Streamlit web application dashboard
├── data.csv                                   # Raw transactional dataset
├── cleaned_ecommerce_data.csv                 # Cleaned dataset ready for analysis
├── customer_summary.csv                       # Customer-level aggregated metrics
├── country_revenue.csv                        # Aggregated revenue by country
├── requirements.txt                           # Project dependencies
├── correlation_heatmap.png                    # Heatmap visualization artifact
├── linear_regression_actual_vs_predicted.png # Model performance visualization
├── order_value_distribution.png              # Order value distribution chart
├── revenue_by_country.png                     # Country revenue chart
├── sales_by_dayofweek.png                     # Weekly sales pattern chart
├── sales_by_hour.png                          # Hourly sales pattern chart
├── top_customers.png                          # Top customers visual chart
├── top_products_quantity.png                  # Top products by quantity chart
└── top_products_revenue.png                   # Top products by revenue chart
```

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure Python 3.8+ and `pip` are installed on your machine.

### 2. Installation

Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/Jaya247/e_commerce-_analysis-_dashboards.git
cd e_commerce-_analysis-_dashboards
```

Install the required Python packages:
```bash
pip install -r requirements.txt
```

### 3. Running the Streamlit Dashboard

Launch the interactive web dashboard locally:
```bash
streamlit run ap.py
```

The application will open automatically in your browser at `http://localhost:8501`.

---

## 👤 Author

**Jaya Maurya**
- GitHub: [@Jaya247](https://github.com/Jaya247)
- Email: `jayamaurya247@gmail.com`

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
