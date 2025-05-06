# car_price_predictor
A machine learning project to predict used car prices based on various features like year, fuel type, transmission, and more.
This project uses supervised machine learning techniques to estimate the selling price of a used car. We explore data preprocessing, feature engineering, categorical encoding, model building using pipelines, and model evaluation using regression metrics.
- **Libraries:**  
  - `pandas`, `numpy` – Data manipulation  
  - `matplotlib`, `seaborn` – Visualization  
  - `scikit-learn` – Machine Learning (models, pipelines, encoding)

Project Steps

1. **Data Cleaning** – Remove irrelevant columns, handle outliers
2. **Feature Engineering** – Create new features like `car_age`
3. **Encoding Categorical Variables** – Using `OneHotEncoder` and `ColumnTransformer`
4. **Model Building** – Linear Regression, Ridge, Lasso, Random Forest
5. **Pipeline Construction** – Combine preprocessing and modeling
6. **Evaluation** – Using R² score, residual plots, and scatter plots

The best-performing model so far achieves:
- **R² Score:** ~0.70 (after improvements with Random Forest)
