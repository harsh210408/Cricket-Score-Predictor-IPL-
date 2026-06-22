# 🏏 Cricket Score Predictor using Machine Learning

An end-to-end Machine Learning and Sports Analytics project that predicts the final first-innings IPL score based on live match conditions such as current score, overs played, wickets, run rate, venue, batting and bowling teams, and recent match momentum.

The project uses feature engineering, exploratory data analysis (EDA), and Random Forest Regression to generate realistic score predictions.

---

# 🚀 Features

✅ Predict IPL first innings final score in real time

✅ Uses historical IPL ball-by-ball and match datasets (2008–2022)

✅ Feature engineering for cricket-specific insights

✅ Live score prediction engine

✅ Interactive and stylish console interface

✅ Model persistence using Joblib

✅ Professional project structure suitable for resume and GitHub

---

# 🎯 Problem Statement

Predicting the final score of a T20 innings is a challenging task because it depends on multiple factors such as:

* Current Score
* Overs Played
* Wickets Lost
* Current Run Rate
* Venue Conditions
* Batting Team
* Bowling Team
* Recent Momentum
* Tail-End Situation

This project uses Machine Learning to forecast the final innings score based on live match statistics and historical IPL data.

---

# 🏗️ Project Architecture

IPL Match Dataset
↓
Data Cleaning
↓
Feature Engineering
↓
Exploratory Data Analysis (EDA)
↓
Train-Test Split
↓
Random Forest Regression Model
↓
Model Evaluation
↓
Live Score Prediction Engine
↓
Prediction Reports

---

# 📂 Project Structure

Cricket-Score-Predictor/

│

├── datasets/

│ ├── IPL_Ball_by_Ball_2008_2022.csv

│ └── IPL_Matches_2008_2022.csv

│

├── models/

│ └── cricket_model.pkl

│

├── notebooks/

│ └── Cricket_Score_Prediction.ipynb

│

├── app.py

├── main.py

├── requirements.txt

├── README.md

└── .gitignore

---

# 🧠 Machine Learning Workflow

## 1. Data Collection

Datasets Used:

* IPL Ball-by-Ball Dataset (2008–2022)
* IPL Match Dataset (2008–2022)

---

## 2. Data Preprocessing

* Handling Missing Values
* Removing Invalid Records
* Selecting First Innings Data
* Creating Current Score
* Calculating Wickets Lost
* Calculating Current Run Rate
* Calculating Balls Left

---

## 3. Feature Engineering

Features Used:

1. Venue
2. Batting Team
3. Bowling Team
4. Current Over
5. Current Score
6. Extras Runs
7. Wickets Left
8. Current Run Rate
9. Balls Left
10. Runs in Last 5 Overs
11. Wickets Lost in Last 5 Overs
12. Venue Average Score
13. Innings Phase
14. Tail-End Situation
15. Death Risk
16. Balls Per Wicket

---

# 🤖 Machine Learning Model

Algorithm Used:

### Random Forest Regression

Reason for Choosing:

* Handles Non-Linear Relationships
* High Prediction Accuracy
* Robust to Outliers
* Works Well on Tabular Sports Data
* Captures Complex Cricket Patterns

---

# 📈 Evaluation Metrics

The model was evaluated using:

### Mean Absolute Error (MAE)

Measures average prediction error in runs.

### Root Mean Squared Error (RMSE)

Measures prediction error while penalizing larger mistakes.

### R² Score

Measures how well the model explains the variance in the data.

---

# 🏆 Model Performance

Example Performance:

MAE : ~8 Runs

RMSE : ~11 Runs

R² Score : ~0.84

This means the model can explain approximately 84% of the variance in IPL first-innings scores.

---

# 🏏 Sample Prediction

Input:

Venue: Narendra Modi Stadium

Batting Team: Royal Challengers Bangalore

Bowling Team: Gujarat Titans

Current Score: 123/4

Overs Played: 12.3

Current Run Rate: 10.0

Runs in Last 5 Overs: 45

Wickets in Last 5 Overs: 1

Output:

Predicted Final Score: 191 Runs

Predicted Range: 186–196 Runs

Match Insight: Competitive Total Expected

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib
* Jupyter Notebook
* Google Colab
* Git
* GitHub

---

# 📦 Installation

Clone the repository:

git clone https://github.com/your-username/Cricket-Score-Predictor.git

cd Cricket-Score-Predictor

Install dependencies:

pip install -r requirements.txt

Run the project:

python main.py

---

# 📌 Future Improvements

* Streamlit Web Application
* Flask REST API
* XGBoost and LightGBM Models
* Deep Learning Models (LSTM)
* Win Probability Prediction
* Second Innings Score Prediction
* Real-Time Cricbuzz API Integration
* Interactive Dashboard
* Player-Level Analytics

---

# 💡 Key Learnings

* Data Cleaning and Preprocessing
* Feature Engineering
* Exploratory Data Analysis
* Regression Algorithms
* Model Evaluation
* Model Persistence
* Sports Analytics
* End-to-End Machine Learning Workflow
* Building Production-Ready ML Projects

---

# 🎓 Project Outcome

Successfully built an end-to-end Machine Learning and Sports Analytics system capable of predicting IPL first-innings scores using historical data and live match statistics with realistic score forecasting and analytical insights.

---

# 👨‍💻 Author

Harsh Jain

B.Tech Student | Machine Learning Enthusiast | Sports Analytics Enthusiast

GitHub: https://github.com/harsh210408

LinkedIn: https://linkedin.com/in/harsh-jain210408
