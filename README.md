🚦 Traffic Volume Prediction with Machine Learning

Key points-
Traffic Volume Prediction with Supervised ML
✅ Data preprocessing & feature engineering (time, weekdays, weekends, etc.)
✅ Exploratory Data Analysis (traffic patterns over hours, days, weeks)
✅ Model building with Linear Regression & Random Forest
✅ Model evaluation using RMSE & R²
✅ Visualization of actual vs predicted traffic
✅ Reflection on what the model learned about traffic behavior
✅ Sequential model (GRU) to explore deep learning for time-series prediction

---

This project focuses on predicting traffic volume using supervised machine learning techniques. It was completed as a practical exam project and covers the full ML workflow—from data preprocessing to model evaluation and interpretation.

📌 Project Overview

Goal: Predict hourly traffic volume using historical traffic data
Dataset: Kaggle – Traffic Prediction Dataset
Platform: Google Colab
Approach: Supervised regression & time-series analysis

🧠 Methods Used

Data Preprocessing
Handling missing values
Feature engineering (Hour, Day of Week, Weekend)
Lag features for time dependency
Feature normalization
Exploratory Data Analysis (EDA)
Traffic trends over time
Hourly and weekly traffic patterns
Identification of rush hours and weekend effects
Models
Linear Regression (baseline)
Random Forest Regressor (primary model)
(Optional) GRU (deep learning for sequence modeling)
Evaluation Metrics
RMSE (Root Mean Squared Error)
R² Score

📊 Key Findings

Traffic shows strong daily and weekly seasonality
Rush hours (morning & evening) have the highest traffic
Random Forest outperforms Linear Regression
Models capture regular patterns but struggle with rare traffic spikes

▶️ How to Run

Open shestem-assignment.ipynb in Google Colab
Upload your kaggle.json file when prompted
Run all cells from top to bottom
All results and plots will be generated automatically

🔗 Dataset

Traffic Prediction Dataset (Kaggle):
https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset

📚 Learning Outcome

This project improved my understanding of:
Time-series feature engineering
Model comparison and evaluation
Feature importance and model limitations
Real-world interpretation of ML predictions


👩‍💻 Author

Saima Chowdhury
CSE Graduate | ML & AI Enthusiast
