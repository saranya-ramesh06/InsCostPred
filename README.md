# Insurance Cost Prediction

## 📌 Project Overview

This project aims to predict medical insurance costs based on demographic and lifestyle factors such as age, BMI, smoking habits, gender, dependents, and region. The goal is to analyze the dataset, extract insights, and compare different machine learning models to determine the best-performing model.

## 📊 Dataset Information

- *Filename*: Insurance.csv
- *Features*:
  - age: Age of the insured person
  - sex: Gender (male/female)
  - bmi: Body Mass Index (BMI)
  - children: Number of dependents
  - smoker: Smoking status (yes/no)
  - region: Residential region
  - charges: Medical insurance cost (Target Variable)

## 🔍 Exploratory Data Analysis (EDA)

- Data profiling using ydata_profiling
- Statistical summaries and missing value analysis
- Visualizations (histograms, pair plots, correlation heatmaps)

## 🤖 Machine Learning Models Used

Several machine learning models were trained and evaluated to compare their predictive performance:

1. *Linear Regression*
2. *Decision Tree Regressor*
3. *Random Forest Regressor*
4. *Gradient Boosting Regressor*
5. *XGBoost Regressor*
6. *K-Nearest Neighbors (KNN) Regressor*
7. *MLP Regressor (Neural Network)*

## 📈 Model Evaluation Metrics

The models were evaluated using the following metrics:

- *Mean Absolute Error (MAE)*
- *Mean Squared Error (MSE)*
- *Root Mean Squared Error (RMSE)*
- *R² Score*

## 🛠 Hyperparameter Tuning

- *RandomizedSearchCV* and *GridSearchCV* were used for hyperparameter optimization.

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies

bash
pip install -r requirements.txt


### 2️⃣ Run the Jupyter Notebook

bash
jupyter notebook PRCP-1021-InsCostPred.ipynb


## 📌 Key Insights

- *Smoking is a major factor affecting insurance costs*, with smokers having significantly higher premiums than non-smokers.
- *Higher BMI leads to increased medical expenses*, suggesting that obesity-related health risks impact insurance costs.
- *Age is directly proportional to insurance charges*, with older individuals incurring higher costs due to increased health risks.
- *Region has a minor effect on insurance charges*, implying that geographical location does not significantly influence pricing.
- *Individuals with more children tend to have slightly higher medical costs*, possibly due to dependent coverage adjustments.
- *Random Forest and XGBoost models performed the best in terms of accuracy*, making them ideal candidates for real-world cost prediction applications.
- *These insights can help insurance companies optimize pricing strategies and improve profitability* by offering competitive premiums based on risk assessment.

## 📜 Conclusion

This project provides a comprehensive analysis of medical insurance cost prediction using multiple machine learning models. The findings can help insurance companies improve risk assessment and pricing strategies. By leveraging machine learning insights, insurers can offer personalized premiums, optimize cost structures, and increase overall profitability.
