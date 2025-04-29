# Gold-Price-USD-INR-Prediction-using-Machine-Learning
Gold Price &amp; USD/INR Prediction using Machine Learning


 Technologies Used
Python

yfinance, requests, BeautifulSoup – for real-time data retrieval and web scraping

Pandas, NumPy – data preprocessing and manipulation

Matplotlib, Seaborn – data visualization

Scikit-learn – machine learning (Simple Linear Regression, StandardScaler, RandomizedSearchCV)

Gradio – interactive web interface for deployment

Pickle – model serialization and loading

📈 Project Overview
This project focuses on building a machine learning pipeline to predict gold prices and USD to INR currency exchange rates using historical and financial data.

🔍 Key Features:
Real-Time Data Retrieval:

Utilized yfinance and requests to collect real-time financial data.

Implemented web scraping using BeautifulSoup to enhance data sources.

Data Preprocessing & Visualization:

Cleaned and structured time series data using Pandas.

Applied StandardScaler for feature normalization.

Visualized historical trends and patterns using Matplotlib and Seaborn.

Model Development:

Built a Simple Linear Regression model using Scikit-learn.

Enhanced performance using RandomizedSearchCV for hyperparameter tuning.

Evaluated using regression metrics (MAE, MSE, R² Score).

Deployment:

Created a Gradio web interface for real-time prediction.

Saved and reloaded trained models with Pickle for seamless deployment.
