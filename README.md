# 📊 Sales Analysis & Forecasting Project  

## 📌 Project Overview  
This project focuses on analyzing historical sales data and building forecasting models to predict future sales trends.  
The goal is to extract insights that help businesses in:  
- **Inventory Planning**  
- **Revenue Forecasting**  
- **Customer & Product Insights**  
- **Strategic Decision Making**  

This project was done as part of my internship at **Codec Technologies**.  

---

## 🗂️ Dataset Description  
The dataset contains detailed sales records with the following key features:  
- **Order Information**: Order ID, Order Date, Ship Date, Sales  
- **Product Information**: Product ID, Category, Sub-Category, Product Name  
- **Customer Information**: Customer ID, Name, Segment  
- **Location Information**: Country, City, State, Region  
- **Other Attributes**: Ship Mode, Postal Code  

---

## 🔑 Project Workflow  

### 1. Data Preprocessing  
- Handling missing values & duplicates  
- Converting date columns  
- Aggregating daily → monthly sales  
- Feature engineering: Month, Year, Region, Category, Lag features  

### 2. Exploratory Data Analysis (EDA)  
- 📈 Sales Trend Analysis  
- 🏷️ Sales by Category & Sub-Category  
- 🌍 Regional & State-wise Sales Heatmaps  
- 👥 Customer Segment Analysis  
- 🏆 Top 10 Products (Pareto Analysis)  
- 📅 Seasonality Heatmap  

### 3. Time Series Analysis  
- Seasonal Decomposition (Trend, Seasonality, Residuals)  
- Stationarity Tests (ADF Test)  

### 4. Forecasting Models  
- Baseline Models (Naïve, Moving Average)  
- Auto-ARIMA (pmdarima)  
- Random Forest & Gradient Boosting with lag features  

### 5. Model Evaluation  
- Metrics: MAE, RMSE  
- Residual Diagnostics (error distribution, autocorrelation)  
- Visual comparison of forecasts vs actual sales  

### 6. Future Forecasting  
- 12-month ahead forecasts with confidence intervals  
- Model comparison: ARIMA vs ML  

---

## 📊 Visualizations Included  
- Sales trend lines  
- Region & category-wise bar charts  
- Seasonality heatmap  
- Pareto charts (80/20 rule for products/customers)  
- Forecast plots with confidence bands  
- Residual diagnostics plots  

---

## 🛠️ Tech Stack  
- **Python** (Pandas, Numpy)  
- **Visualization**: Matplotlib, Seaborn, Plotly  
- **Forecasting**: Statsmodels, pmdarima  
- **Machine Learning**: Scikit-learn (RandomForest, GradientBoosting)  
- **Google Colab** for execution  

---

## 📌 Key Insights  
- Sales show strong **seasonality** with peaks during specific months.  
- **Furniture and Electronics** categories contribute most revenue.  
- Certain **regions outperform others**, giving expansion opportunities.  
- Machine Learning models outperformed ARIMA in capturing complex patterns.  

---

## 🚀 How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/sales-forecasting.git
   cd sales-forecasting
