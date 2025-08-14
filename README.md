# Solana Sentiment Price Prediction

This project analyzes sentiment and market data for the Solana cryptocurrency to predict short-term price movements using multiple machine learning models.

## Methodology
- Collected sentiment metrics and market indicators (price, volume, volatility).
- Engineered features such as rolling averages and sentiment ratios.
- Trained and compared four ML models:
  - Random Forest
  - Logistic Regression
  - Support Vector Machine (SVM)
  - XGBoost

## Results

| Model               | Accuracy | F1 Score | ROC-AUC |
|---------------------|----------|----------|---------|
| Random Forest       | 0.68     | 0.69     | 0.76    |
| Logistic Regression | 0.60     | 0.61     | 0.64    |
| SVM                 | 0.60     | 0.64     | 0.59    |
| XGBoost             | **0.69** | **0.70** | 0.75    |

Key Insight: Tree-based models (Random Forest, XGBoost) outperform linear models, indicating a non-linear relationship between sentiment and price.
