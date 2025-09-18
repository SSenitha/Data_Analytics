
# 🌦️ Rain Prediction Using Australian Weather Data

This project analyzes a decade of daily weather observations from various locations across Australia to predict whether it will rain the next day. It combines descriptive statistics, inferential analysis, and machine learning techniques to build a robust predictive model.

### 🧑‍💼 Contributors
- Dilini Sewwandi
- Sandaru Senitha
- Aashinshana Weerakoon

## 📁 Project Structure

- `data/` – Raw and cleaned datasets
- `notebooks/` – Jupyter notebooks for descriptive, inferential, and predictive analysis
- `models/` – Trained models and evaluation metrics
- `report/` – Final report document and visualizations
- `README.md` – Project overview and instructions

## 📊 Objectives

- Understand historical weather patterns across Australia
- Identify key meteorological factors influencing rainfall
- Build a machine learning model to predict next-day rain (`RainTomorrow`)
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC

## 🧪 Methodology

1. **Preprocessing**  
   - Removed duplicates and handled missing values  
   - Dropped irrelevant columns  
   - Converted data types and engineered temporal features

2. **Analysis**  
   - Descriptive statistics and visualizations  
   - Correlation and distribution analysis  
   - Hypothesis testing using Mann–Whitney U, Chi-square, and Kruskal–Wallis tests

3. **Model Training**  
   - Algorithms: Logistic Regression, Random Forest, XGBoost  
   - Addressed class imbalance using class weighting  
   - Final model: Tuned XGBoost with 84.7% accuracy and 70% recall

## 🔍 Key Findings

- **Humidity at 3PM** is the most significant predictor of rainfall
- Rainfall patterns vary significantly across cities
- Lower atmospheric pressure and higher cloud cover are strong indicators of rain

## 🚀 Applications

- **Agriculture** – Irrigation and crop planning  
- **Event Planning** – Weather contingency strategies  
- **Logistics** – Route optimisation and delay forecasting  
- **Water Management** – Reservoir and dam operations

## 📌 Future Work
- Improve precision-recall trade-off  
- Develop location-specific models  
- Integrate real-time weather data for live predictions

## 📎 Resources

- Descriptive Analysis Notebook
- [Inferential Analysis Notebook](https://github.com/SSenitha/Data_Analytics/blob/main/Inferential/github/SSenitha/Data_Analytics/blob/Aashi/masterNotebook.ip-


