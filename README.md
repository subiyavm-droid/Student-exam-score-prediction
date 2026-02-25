**STUDENT EXAM SCORE PREDICTION USING EDUCATIONAL DATA MINING WORKFLOW**

📌 **Project Overview**

This project focuses on predicting student exam scores using an Educational Data Mining (EDM) workflow. It analyzes academic, behavioral, and environmental factors such as study hours, attendance, sleep quality, internet access, study methods, and exam difficulty to estimate student performance.

Two regression models were developed and compared to determine the most effective predictive approach.

📊 **Dataset Information**

Total Records: 20,000 students

Total Features: 13 columns

Target Variable: exam_score

🔄 **Educational Data Mining Workflow**

1️⃣ **Data Preprocessing**

Removed duplicate records

Verified no missing values

Encoded categorical variables using LabelEncoder

Applied feature scaling using StandardScaler

2️⃣ **Exploratory Data Analysis (EDA)**

Correlation heatmap to identify relationships

Exam score distribution analysis

Feature importance visualization

3️⃣ **Model Development**

Train-Test Split (80% training, 20% testing)

Linear Regression

Random Forest Regressor (200 estimators)

4️⃣ **Model Evaluation Metrics**

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

R² Score (Coefficient of Determination)

📈 **Model Performance**

🔹 Linear Regression

MAE: 8.80

RMSE: 10.90

R² Score: 0.667

🌲 **Random Forest Regressor**

MAE: 8.44

RMSE: 10.45

R² Score: 0.694

✅ The Random Forest model achieved better predictive performance compared to Linear Regression.

🏆 **Key Insights**

Higher study hours and class attendance strongly correlate with better exam performance.

Sleep hours and exam difficulty significantly influence student scores.

Ensemble models improve prediction accuracy over traditional linear models.

Educational data mining techniques can help institutions identify students who may need academic support.

🛠️ **Technologies Used**

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook / Google Colab

👩‍💻 **Author**

Subiya V M
