📈 Netflix Stock Price Prediction
Welcome to the Netflix Stock Price Prediction project!
This repository contains a full machine learning pipeline to analyze, visualize, and predict Netflix's stock prices based on historical market data.

🛠️ Project Structure
EDA (Exploratory Data Analysis):

Understanding the dataset

Handling missing values and duplicates

Outlier detection

Data visualization (distplots, boxplots, heatmaps, pairplots)

Data Preprocessing:

Feature extraction from Date (Year, Month, Day)

Encoding and scaling

Train-test split

Model Building:

Linear Regression

Random Forest Regressor

Performance comparison (MSE, R² Score)

Evaluation:

Model performance metrics

Visual comparison

📂 Dataset
The dataset contains daily Netflix stock information, including:


Column	Description
Date	Trading date
Open	Opening stock price
High	Highest price of the day
Low	Lowest price of the day
Close	Closing stock price
Adj Close	Adjusted closing price
Volume	Number of shares traded
Data Source: Yahoo Finance

🚀 Technologies Used
Python 3

Pandas for data handling

NumPy for numerical operations

Seaborn and Matplotlib for visualizations

Scikit-learn for machine learning models and preprocessing

🧠 Models Applied

Model	Description
Linear Regression	Simple baseline model
Random Forest Regressor	Ensemble model capturing non-linear patterns
Each model is evaluated using:

Mean Squared Error (MSE)

R² Score (Coefficient of Determination)

📊 Results

Model	MSE (Lower is better)	R² Score (Higher is better)
Linear Regression	value	value
Random Forest Regressor	value	value
🔵 Random Forest consistently outperforms Linear Regression by capturing complex trends in stock price movements.



✅ Future Improvements
Add technical indicators (RSI, Moving Averages, MACD)

Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)

Deep Learning models (LSTM, GRU for time series forecasting)

🧑‍💻 Author
Dhruv Gupta

🌟 Show your support!
If you find this project helpful, please ⭐ star this repository to keep me motivated!

📢 License
This project is licensed under the MIT License.

