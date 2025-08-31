✈️ Flight Price Prediction
📌 Project Overview

Flight ticket prices vary based on multiple factors such as airline, source, destination, number of stops, and journey time.
This project aims to predict flight prices using machine learning models by analyzing historical flight data.

The goal is to build a model that helps travelers, airlines, and travel platforms estimate flight fares more accurately.

📂 Dataset

Source: Kaggle – Flight Price Prediction Dataset

Key Features:

Airline – Airline company

Date_of_Journey – Date of travel

Source – Starting location

Destination – Final location

Route – Flight route details

Dep_Time – Departure time

Arrival_Time – Arrival time

Duration – Total travel duration

Total_Stops – Number of stops

Price – Ticket price (Target variable)

⚙️ Methodology

Data Cleaning & Preprocessing

Handle missing values

Convert date/time columns to proper format

Encode categorical features (Airline, Source, Destination)

Feature engineering (Journey day/month, time categories)

Exploratory Data Analysis (EDA)

Visualized airline-wise ticket prices

Impact of total stops on price

Price variation by journey month and route

Model Building

Implemented multiple ML models:

Linear Regression

Decision Tree

Random Forest

Gradient Boosting

Hyperparameter tuning for performance optimization

Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

📊 Results

Random Forest & Gradient Boosting performed best.

Achieved R² score ~0.85 (example — update with your actual result).

Key insights:

Flights with more stops are significantly costlier.

Certain airlines consistently charge higher fares.

Ticket prices vary heavily depending on journey month and seasonality.

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/Flight-Price-Prediction.git


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook Project_1-Flight_Price_Prediction.ipynb

📌 Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Tools: Jupyter Notebook

🙌 Acknowledgements

Dataset from Kaggle
.

Project developed as part of Capstone Project for Data Science learning journey.

✨ Author: Diwakar Kumar
