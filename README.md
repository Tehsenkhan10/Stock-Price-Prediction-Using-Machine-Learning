# Stock-Price-Prediction-Using-Machine-Learning
📈 Stock Price Prediction Using Machine Learning
This project applies regression analysis using historical stock market data to predict the next day's closing price of Apple Inc. (AAPL) shares. The dataset contains daily Open, High, Low, Close, and Volume values from 2006 to 2018, and multiple machine learning models are applied to evaluate predictive performance.

📁 Dataset
Source: Kaggle - All Stocks 2006–2018 Dataset
File Used: all_stocks_2006-01-01_to_2018-01-01.csv
Features:
Open, High, Low, Close, Volume, and Date
Target: Next day’s Close price
🧠 Machine Learning Models Used
Linear Regression
Support Vector Regression (SVR)
Random Forest Regressor
All models are evaluated using:
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
R² Score (Coefficient of Determination)
🛠️ Steps Performed
Unzip & Load Data: Load the ZIP file, extract the CSV, and read into a DataFrame.
Preprocess Data: Filter for AAPL, sort by date, shift for target creation.
Train-Test Split: 80/20 split without shuffling to preserve time series order.
Model Tuning: Grid search applied to optimize SVR and Random Forest.
Evaluation: Predictions plotted against actual values for each model.
Visualization: Line graphs display how closely each model tracks real prices.
📊 Results Summary
Model	MAE ↓	RMSE ↓	R² ↑
Linear Regression	✅ Good	✅ Good	✅ High
SVR (Tuned)	⚠️ Improved after tuning	⚠️ Moderate	⚠️ Moderate
Random Forest (Tuned)	⚠️ Improved after tuning	⚠️ Moderate	⚠️ Moderate
🔧 Requirements
Python 3.7+
pandas, scikit-learn, matplotlib, numpy
bash
Copy
Edit
pip install pandas scikit-learn matplotlib numpy
📂 Folder Structure
kotlin
Copy
Edit
📦 Stock-Price-Prediction-ML
 ┣ 📁 data
 ┃ ┗ 📄 all_stocks_2006-01-01_to_2018-01-01.csv
 ┣ 📄 Stock_Prediction_Notebook.ipynb
 ┣ 📄 README.md
✍️ Author
Tehseen Ullah Saif
AI Student at NUML University
Email: [Tehseenkhan1137@gmail.com]
