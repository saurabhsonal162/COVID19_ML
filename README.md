# COVID19_ML
A machine learning project that predicts COVID-19 deaths using regression techniques and cross-validation for model performance evaluation.
🧠 COVID-19 Regression Project 
🎯 Objective
This project applies Regression and Model Performance concepts to analyze and predict COVID-19 deaths using a real dataset.
It involves data preprocessing, exploratory data analysis (EDA), regression modeling, and cross-validation to assess and improve model performance.

📊 Dataset
File Used: country_wise_latest.csv
The dataset contains country-wise COVID-19 statistics such as:
1.Confirmed cases
2.Deaths
3.Recovered
4.Active cases
5.WHO region
and other relevant metrics.

⚙️ Project Workflow
1️⃣ Data Preprocessing
1.Loaded dataset using Pandas.
2.Dropped non-numeric and irrelevant columns (Country/Region, WHO Region).
3.Handled missing and infinite values using median imputation.
4.Split data into training (80%) and testing (20%) sets.

2️⃣ Exploratory Data Analysis (EDA)

Statistical summary of dataset.

Correlation heatmap between all numeric features.

Scatter plot showing relationship between Confirmed cases and Deaths.

3️⃣ Regression Models

Two models were implemented and compared:
1.Multiple Linear Regression – baseline model using Ordinary Least Squares (OLS).
2.Random Forest Regression – ensemble method using Bagging to reduce variance.

4️⃣ Model Evaluation

Performance metrics used (Unit II):

1.MAE (Mean Absolute Error)

2.MSE (Mean Squared Error)

3.RMSE (Root Mean Squared Error)

4.R² Score (Coefficient of Determination)

5️⃣ Cross-Validation (Unit VI)

5-Fold Cross Validation used for both models.

Compared average R² values to assess model stability.

6️⃣ Bias-Variance Discussion

Visualized residuals of Random Forest predictions.

Discussed trade-offs between model complexity and generalization.

🧮 Libraries Used
Library	Purpose
pandas	Data loading and cleaning
numpy	Numerical operations
matplotlib, seaborn	Data visualization
scikit-learn	Regression, Cross-validation, Metrics


✅ Random Forest performed better due to its ensemble nature, capturing non-linear patterns effectively and reducing variance.

📈 Visual Outputs

Correlation Heatmap

Scatter plot: Confirmed vs Deaths

Residuals vs Predicted (Random Forest)
