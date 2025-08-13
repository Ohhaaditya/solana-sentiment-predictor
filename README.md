
---

## Methodology

1. **Data Collection**  
   - On-chain sentiment metrics for Solana from [data source(s)].
   - Market indicators: price, volume, volatility, moving averages.

2. **Feature Engineering**  
   - Processed sentiment scores (positive/negative/neutral ratios).
   - Rolling averages and lag features for market variables.
   - Combined sentiment and market features into a single dataset.

3. **Modeling**  
   - Trained and tested multiple machine learning models:
     - Random Forest
     - Logistic Regression
     - Support Vector Machine (SVM)
     - XGBoost
   - Used 70/30 train-test split and stratified sampling.
   - Evaluated models with Accuracy, F1 Score, and ROC-AUC.

4. **Evaluation Results**

| Model               | Accuracy | F1 Score | ROC-AUC |
|---------------------|----------|----------|---------|
| Random Forest       | 0.68     | 0.69     | 0.76    |
| Logistic Regression | 0.60     | 0.61     | 0.64    |
| SVM                 | 0.60     | 0.64     | 0.59    |
| XGBoost             | **0.69** | **0.70** | 0.75    |

**Key Finding:**  
Tree-based models (Random Forest, XGBoost) significantly outperform linear models, suggesting the price-sentiment relationship is non-linear.

