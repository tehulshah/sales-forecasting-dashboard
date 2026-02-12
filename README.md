# 📊 Sales Forecasting & Business Insights Dashboard

## 📌 Project Overview
This project analyzes historical retail sales data to generate business insights and forecast future sales using time-series modeling. An interactive Power BI dashboard is developed to visualize trends, regional performance, and product-level insights.

The goal is to help businesses understand sales behavior and make data-driven decisions for future planning.

---

## 🎯 Objectives
- Analyze historical sales patterns
- Identify top-performing regions and products
- Detect seasonal trends
- Forecast future sales
- Build an interactive business dashboard

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Prophet (Time-Series Forecasting)
- Power BI
- Scikit-learn
- Pickle

---

## 📂 Project Structure

```text
sales-forecasting-project/
│
├── data/
│   └── raw_sales_data.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_EDA.ipynb
│   └── 03_sales_forecasting.ipynb
│
├── dashboard/
│   └── sales_dashboard.pbix
│
├── models/
│   └── forecasting_model.pkl
│
├── outputs/
│   └── forecast_results.csv
│
└── README.md
```

---

## 📊 Dashboard Features
- Total Sales & Orders KPI
- Monthly Sales Trend
- Regional Sales Performance
- Category Sales Analysis
- Top Products
- Sales Forecast for Next 12 Months
- Interactive Filters (Region & Category)

---

## 🔮 Forecasting Approach
- Sales aggregated monthly
- Prophet model used for forecasting
- Future sales predicted for next 12 months
- Model performance evaluated using MAE

---

## 📈 Key Insights
- Sales show seasonal peaks toward year-end.
- Few products contribute major revenue.
- Regional sales performance varies significantly.
- Forecast predicts steady growth trend.

---

## 🚀 Business Impact
This solution can help organizations:
- Plan inventory
- Optimize regional strategy
- Forecast revenue
- Identify high-performing products

---

## ▶️ How to Run the Project
1. Install dependencies
```bash
pip install pandas numpy matplotlib prophet scikit-learn
```
2. Run notebooks in order:

- 01_data_cleaning.ipynb
- 02_EDA.ipynb
- 03_sales_forecasting.ipynb

3. Open Power BI dashboard file to explore insights.

## 📌 Future Improvements
- Add profit forecasting
- Deploy forecasting API
- Automate data pipeline
- Add customer segmentation

## 👨‍💻 Author
Tehul Shah - 
Data Science Enthusiast

## ⭐ Acknowledgment

Dataset sourced from: 
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

---