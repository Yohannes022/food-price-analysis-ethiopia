# 🇪🇹 Food Price Analysis in Ethiopia

## 📊 Project Overview

This project analyzes food price trends across Ethiopia using real-world data. The goal is to understand price behavior, identify regional differences, and build predictive models for food pricing.

---

## 🎯 Objectives

* Analyze food price trends over time
* Identify regional and market-level price variations
* Understand key factors influencing food prices
* Build machine learning models to predict prices

---

## 🧹 Data Processing

* Cleaned raw dataset by handling missing values and removing duplicates
* Converted date fields and engineered time-based features (year, month)
* Filtered dataset to focus on retail prices

---

## 📊 Exploratory Data Analysis (EDA)

Key findings:

* Food prices show a consistent upward trend, indicating inflation
* Price distribution is highly skewed due to high-value livestock commodities
* Significant regional and market-level price differences exist
* Maize appears to be a widely available staple with relatively stable prices

---

## 🤖 Modeling Approach

### Model Type

* Random Forest Regressor

### Strategy

To improve model performance, the dataset was segmented into:

* **Food commodities model**
* **Livestock commodities model**

---

## 📈 Model Performance

| Model           | MAE     | R²   |
| --------------- | ------- | ---- |
| Food Model      | 446.86  | 0.94 |
| Livestock Model | 2990.70 | 0.89 |

---

## 🧠 Key Insights

* Commodity type is the most influential factor in price prediction
* Livestock commodities dominate the high-price range
* Time (year) significantly impacts prices, confirming inflation trends
* Segmenting the dataset improves model performance and interpretability

---

## ⚠️ Limitations

* Dataset includes both food and livestock, which differ significantly in price scale
* External factors (transport, demand, seasonality) are not included
* Some extreme values may influence model performance

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy, Scikit-learn)
* Data Visualization (Matplotlib, Seaborn)
* Jupyter Notebook

---

## 📂 Project Structure

* `data/` → Raw and processed datasets
* `notebooks/` → Data cleaning, EDA, and modeling notebooks
* `outputs/` → Visualizations

---

## 👤 Author

**Yohannes Tesfaye**
Addis Ababa, Ethiopia

---

## 🚀 Future Improvements

* Apply time-series forecasting models (ARIMA, Prophet)
* Deploy model as an API
* Build interactive dashboard
