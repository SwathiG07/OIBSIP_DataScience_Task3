# Task 3: Car Selling Price Prediction

## Objective
Predict the selling price of cars using machine learning models: Linear Regression, Random Forest Regressor, and XGBoost Regressor.

## Steps Performed
1. Loaded the "car data.csv" dataset and stripped extra spaces from column names.
2. Label encoded categorical columns:
   - `Car_Name`, `Fuel_Type`, `Selling_type`, `Transmission`.
3. Removed duplicate rows from the dataset.
4. Split the dataset into features (`X`) and target (`y`), with `Selling_Price` as the target.
5. Performed an 80-20 train-test split.
6. Trained and evaluated three models:
   - **Linear Regression**
   - **Random Forest Regressor**
   - **XGBoost Regressor**
7. Evaluated models using **R² score** and **Mean Absolute Error (MAE)**.

## Tools / Technologies Used
- Python 3.12
- Pandas, NumPy  
- scikit-learn (`LinearRegression`, `RandomForestRegressor`, `train_test_split`, `LabelEncoder`, `r2_score`, `mean_absolute_error`)  
- XGBoost (`XGBRegressor`)  
- Jupyter Notebook or Google Colab  

## Outcome / Results
- **Linear Regression**
  - R² Score: [73.5 %]  
  - MAE: [1.57]  
- **Random Forest Regressor**
  - R² Score: [59.09 %]
  - MAE: [1.37]  
- **XGBoost Regressor**
  - R² Score: [79.72%]  
  - MAE: [1.02]  
- XGBoost outperform Linear Regression and Random Forest Regressor for predicting car selling prices.

