# Airbnb Barcelona Price Prediction

This project predicts Airbnb listing prices in Barcelona using a machine learning pipeline:
- 📊 Exploratory Data Analysis (EDA)
- 🛠 Feature Engineering (FE)
- 📈 Model Training (LightGBM, CatBoost, XGBoost)
- 💡 SHAP for explainability
- 📈 Visualizations & feature importance

## Data
Dataset: Airbnb Barcelona listings (public Kaggle dataset or scraped data).

## Key Findings
- Geospatial location is critical for predicting price.
- Number of reviews, minimum nights, and availability also impact price.
- SHAP reveals the top drivers behind pricing decisions.

## Requirements
Install packages from requirements.txt
```bash
pip install -r requirements.txt
