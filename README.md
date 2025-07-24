README: Loan Amount Prediction using Linear Regression
-------------------------------------------------------

🔍 Objective:
To predict the loan amount sanctioned to users based on financial, demographic, and property-related features using a Linear Regression model.

🛠️ Tools & Libraries Used:
- Python
- Pandas, NumPy
- Scikit-learn (for preprocessing, model building, and evaluation)
- Matplotlib, Seaborn (for data visualization)

🧪 Workflow Summary:
1. Load the dataset from Kaggle.
2. Preprocess the data: handle missing values, encode categorical variables, and scale numeric features.
3. Build a pipeline using Pipeline and ColumnTransformer for clean preprocessing and modeling.
4. Train the Linear Regression model on the training set.
5. Evaluate the model using MAE, MSE, RMSE, R², and Adjusted R². Visualize residuals, predictions, and feature importance.

📈 Results:
- The model demonstrated reliable predictive performance with minimal signs of overfitting.
- Visual diagnostics (residual plots, predicted vs actual) supported linearity and variance assumptions.
- Features like Credit Score and Income were among the most influential in loan amount prediction.
