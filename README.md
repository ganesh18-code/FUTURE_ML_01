# 📊 AI-Powered Sales Forecasting

This project is an **AI-powered Sales Forecasting System** developed as part of an internship task.  
It uses **time-series models (Prophet, SARIMA, XGBoost)** and **ensemble forecasting** to predict sales, and visualizes insights through a **Power BI dashboard**.

---

## 🚀 Key Features
- ✅ Data preprocessing and feature engineering (monthly sales trends, seasonality, YoY & MoM growth).
- ✅ Forecasting with:
  - Facebook Prophet  
  - SARIMA (Statsmodels)  
  - XGBoost Regressor  
- ✅ Ensemble model (averaging multiple forecasts for improved accuracy).  
- ✅ Insights:
  - Top-selling products  
  - Seasonal demand fluctuations  
  - Regional/Category/Store-level trends  
- ✅ Power BI Dashboard:
  - Actual vs Forecast comparison  
  - Monthly and yearly growth analysis  
  - Insight cards for decision-making  

---

## 📂 Project Structure
FUTURE_ML_01/
│
├── dataset/
│ ├── sample - Superstore.csv # Raw monthly sales data
│ 
│
├── notebooks/
│ ├── ai_powered_salesforecasting.ipynb  # Kaggle notebook with model training & analysis
│
├── dashboard/
│ ├── salesforecast.pbix # Power BI dashboard
│
├── README.md # Project documentation
└── requirements.txt # Python dependencies

---

## ⚙️ How to Run
# Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-sales-forecasting.git
   cd ai-sales-forecasting
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook notebooks/forecasting.ipynb

# requirements.txt :
```txt
pandas
numpy
matplotlib
prophet
statsmodels
xgboost
scikit-learn
Run all cells to:

Preprocess sales data

Train Prophet, SARIMA, XGBoost models

Generate ensemble forecast

Export forecast CSVs

---

## 📊 Power BI Dashboard
Open dashboard/sales_forecast.pbix in Power BI Desktop.

Connect to data/monthly_sales.csv & data/ensemble_forecast.csv.

Explore:

- Actual vs Forecast line chart

- Regional/Category filters

- Insight cards (growth %, top sellers, seasonality)

---

## 🔮 Insights from the Model

- Forecast shows seasonal peaks around March & November.

- Top-selling items drive >40% of revenue.

- Low season observed in Q2 (April–June).

- Ensemble forecast reduces variance vs individual models.

---

## 🧑‍💻 Author

Borra Pujith Ganesh – FUTURE INTERNS - Machine Learning
📧 Contact: pujithganesh18@gmail.com
