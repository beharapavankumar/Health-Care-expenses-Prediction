# 🔷 Health Insurance Expenses Prediction
Objective:
Developed a machine learning model to predict individual medical expenses based on demographic and health-related features using regression techniques.

Key Responsibilities:

Cleaned and preprocessed data (handled categorical variables, dropped less impactful features like region and sex, encoded smoker status).

Performed feature selection to retain impactful predictors such as age, BMI, number of children, and smoking habits.

Explored various regression models including Linear Regression, Polynomial Regression, ElasticNet, Decision Tree Regressor, and XGBoost Regressor.

Implemented hyperparameter tuning using GridSearchCV for optimal performance.

Achieved high accuracy using XGBoost, with:

Train R² Score: 0.86134

Cross-Validation Score: 0.84447

Test R² Score: 0.89931

Exported the final XGBoost model using joblib for future predictions.

Built logic for predicting expenses on new unseen data using the saved model.

Technologies Used:
Python, Pandas, Scikit-learn, ,Different Regression algorithms, BestFit(XGBoost), Matplotlib, Seaborn, EDA, Data Preprocessing, Data Wrangling, Standard ScalarScaling, Feature selection, Feature Engineering, Data Wrangling, Joblib

# Author
Behara Pavan Kumar
