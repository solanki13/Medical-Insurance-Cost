# Medical-Insurance-Cost
This project predicts the medical insurance charges based on patient demographic and lifestyle information using Machine Learning.

### 🔬 **Project Overview**
This project predicts the medical insurance cost (charges) based on demographic and lifestyle data using advanced machine learning models. The system is fully production-ready with complete:

- Data processing pipeline

- Feature engineering

- Model training & hyperparameter tuning

- Model evaluation

- Deployment-ready REST API (Flask)

### 📊**Problem Statement**
Insurance companies often need to predict future charges for individuals based on their profiles. Accurate predictions help in:

- Premium pricing

- Risk management

- Revenue forecasting

The goal is to build a machine learning model which predicts medical charges given attributes like age, sex, BMI, smoking habits, number of children, and residential region.

### 📂 **Dataset**
The dataset used: Medical Cost Personal Dataset

The dataset contains the following features:

- **age:** age of primary beneficiary

- **sex:** gender of insurance contractor

- **bmi:** Body Mass Index

- **children:** number of dependents covered

- **smoker:** smoking status

- **region:** residential area

- **charges:** actual medical costs (target variable)

### 🚀 Technologies Used
- Python 3.9

- pandas, numpy - Data manipulation

- scikit-learn - ML modeling, preprocessing, and hyperparameter tuning

- matplotlib - Visualizations

- joblib - Model persistence

### 🏗 Project Workflow
**1️⃣ Data Preprocessing**

- Handle categorical features using OneHotEncoding

- Scale numerical features using StandardScaler

**2️⃣ Feature Engineering**

- Created new interaction features:

- bmi_smoker = BMI × Smoker

- age_smoker = Age × Smoker

- bmi_age = BMI × Age

**3️⃣ Model Development**

- Used Gradient Boosting Regressor (high performance for tabular data)

- Hyperparameter tuning using GridSearchCV with cross-validation

- 5-fold KFold cross-validation

**4️⃣ Model Evaluation**

Evaluation metrics:

- R² Score

- Mean Absolute Error (MAE)

- Root Mean Squared Error (RMSE)

**Visualizations:**

- Actual vs Predicted Scatter Plot

- Feature Importance Plot

- Cross-Validation Accuracy Curve

**5️⃣ Model Saving**

Final trained model saved using joblib

### 🔎 Future Enhancements
- Add frontend web interface for easy input/output

- Integrate advanced models (XGBoost, LightGBM, CatBoost)

- Model monitoring & drift detection in production

- Database integration for persistent storage

- API authentication for secure production API

