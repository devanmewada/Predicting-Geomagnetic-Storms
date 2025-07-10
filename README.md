# Predicting-Geomagnetic-Storms
Predictive modeling of geomagnetic storms using refined K-index and magnetic field data (EYR)

## 📈 Predicting Geomagnetic Storms

This project explores the short-term prediction of geomagnetic storms using minute-level magnetic field data and a refined version of the planetary K-index. The goal is to improve detection and forecasting accuracy by combining signal processing, time-series analysis, and machine learning techniques.

The dataset comes from the Eyrewell (EYR) observatory in New Zealand and includes vector magnetic field measurements (EYR-X, EYR-Y) alongside imputed and scaled K-index values. The refined K-index uses proportional scaling within H-range bins to introduce greater granularity for modeling.

### 🧠 Key Features
- K-index imputation using KNN for scattered gaps
- Refined K-index construction using |dH/dt| from magnetic field changes
- 3-hour resolution aggregation of minute-level EYR data
- Visual exploration of storm patterns and magnetic disturbances
- Predictive models using lagged K-index values (e.g., Logistic Regression, Random Forest, XGBoost)

### 📦 Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebooks

### 📍 Applications
The refined K-index and modeling pipeline can assist in regional storm monitoring, with potential use in energy systems, infrastructure planning, and space weather forecasting tools.

