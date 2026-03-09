# BMW Global Sales Analysis & Prediction (2018–2025)

## Project Overview

This project analyzes BMW global sales data from 2018 to 2025 and builds a machine learning model to predict car sales based on economic and market factors.

The project demonstrates key Data Science skills including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning Modeling
- Business Insights

---

## Dataset

The dataset contains monthly BMW sales data across multiple regions and models.

Features include:

- Year
- Month
- Region
- Model
- Units Sold
- Average Price (EUR)
- Revenue (EUR)
- BEV Share (Electric Vehicles)
- Premium Share
- GDP Growth
- Fuel Price Index

Total Records: **3072**

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Business Insights

---

## Exploratory Data Analysis

Key visualizations include:

- Sales trends over time
- Regional sales comparison
- Model-wise revenue analysis
- Correlation heatmap

---

## Machine Learning Model

A **Random Forest Regressor** was used to predict:

```
Units_Sold
```

### Evaluation Metrics

- Mean Absolute Error (MAE)
- R² Score

---

## Key Insights

• Europe shows the highest BMW sales.  
• Luxury models contribute the majority of revenue.  
• GDP growth positively impacts vehicle sales.  
• Fuel prices influence purchasing behavior.  
• Electric vehicle share has increased over time.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```
bmw-sales-analysis
│
├── data
│   bmw_global_sales_2018_2025.csv
│
├── notebook
│   bmw_sales_analysis.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## Author

Shaaf Iqbal

GitHub: https://github.com/yourusername

---

## Future Improvements

- Time series forecasting
- Deep learning models
- Interactive dashboards using Power BI or Streamlit
