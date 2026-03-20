# House Price Prediction Using Machine Learning

## Objective
Build a predictive model to estimate house prices using real-world housing dataset and regression algorithms.

## Dataset
- **Source:** Real-world housing dataset
- **Records:** 1,460 houses
- **Features:** 30+ attributes (area, bedrooms, bathrooms, condition, etc.)
- **Target:** Sale price

## Methodology
1. Data preprocessing and feature selection (10 key features identified)
2. Exploratory data analysis with Pandas & Matplotlib
3. Model comparison: Linear Regression vs Random Forest
4. Performance evaluation using RMSE and R² metrics

## Results
- **Linear Regression Accuracy:** 85% (R² = 0.85)
- **Baseline Model Performance:** 72%
- **Improvement:** +13% over baseline
- **Best Model:** Linear Regression (interpretability + performance trade-off)

## Technologies
- Python 3.x
- Pandas, NumPy (data processing)
- Scikit-learn (ML models)
- Matplotlib (visualization)

## How to Use
```bash
python house_price_prediction.py
```

## Key Insights
- Top 3 predictive features: Area, Condition, Year Built
- Linear model captures 85% of price variance
- Feature engineering critical for model performance
