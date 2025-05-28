**Flight Fare Prediction:**

This project aims to build a machine learning model that predicts flight ticket prices based on key travel details like airline, source, destination, journey date, duration, and number of stops. The goal is to provide a reliable prediction tool that can help users make informed booking decisions and assist travel platforms in offering better fare estimates.
 
**Dataset:**

The dataset contains various features such as:

Airline

Source and Destination

Date of Journey

Departure and Arrival Time

Duration

Total Stops

Fare (Target Variable)

**Project Workflow:**

Data Cleaning – Handling missing values and formatting datetime columns

Feature Engineering – Extracting day, month, duration in minutes, and encoding categorical data

Exploratory Data Analysis (EDA) – Understanding the relationships between features and fares

Model Selection – Trying out various regressors like Random Forest, Gradient Boosting, XGBoost

Hyperparameter Tuning – Fine-tuning model parameters for best performance

Model Evaluation – Using metrics like RMSE, R² Score, and MAE to evaluate results

**Best Model:**
The Gradient Boosting Regressor gave the most accurate results with the lowest RMSE and highest R² score.

**Tech Stack:**
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

**Repository Structure:**

flight_fare_prediction.ipynb – Main Jupyter notebook

README.md – Project overview

requirements.txt – Required Python packages

**Outcome:**
Successfully built a robust flight fare prediction model with strong performance metrics. This model can be integrated into real-world travel platforms to enhance price transparency and planning.
