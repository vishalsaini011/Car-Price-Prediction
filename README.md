# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning.

The project analyzes different factors such as car age, kilometers driven, fuel type, seller type, owner details, and transmission type to understand their impact on car selling prices.

A Random Forest Regression model is used to predict car prices and evaluate the performance of the prediction model.

The project also includes an interactive Power BI dashboard for data visualization and analysis.

---

## 🎯 Objectives

- Analyze used car selling price data.
- Perform data preprocessing and feature engineering.
- Identify important factors affecting car prices.
- Build a Machine Learning regression model.
- Predict car selling prices.
- Evaluate model prediction errors.
- Visualize insights using Power BI.

---

## 🗂️ Dataset

The dataset contains information about used cars and their selling prices.

### Important Features

- `car_age` – Age of the car
- `km_driven` – Kilometers driven
- `fuel_Diesel` – Diesel fuel indicator
- `fuel_Electric` – Electric fuel indicator
- `fuel_LPG` – LPG fuel indicator
- `fuel_Petrol` – Petrol fuel indicator
- `seller_type_Individual` – Individual seller indicator
- `seller_type_Trustmark Dealer` – Trustmark dealer indicator
- `owner_*` – Owner-related features
- `transmission_*` – Transmission-related features
- `Actual_Price` – Actual selling price
- `Predicted_Price` – Price predicted by the Machine Learning model
- `Prediction_Error` – Difference between actual and predicted price
- `Absolute_Error` – Absolute prediction error

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook
- Power BI

---

## 🤖 Machine Learning Model

### Random Forest Regression

A **Random Forest Regressor** was used for predicting used car selling prices.

Random Forest combines multiple decision trees to produce a more robust prediction and can capture nonlinear relationships between car features and selling price.

---

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Train-Test Split
      ↓
Random Forest Regression
      ↓
Price Prediction
      ↓
Model Evaluation
      ↓
Power BI Visualization


📊 Model Evaluation

The model predictions were compared with the actual selling prices.
The dataset was also analyzed using:
 1.Prediction Error
 2.Absolute Error
 3.Actual vs Predicted Price visualization
The Power BI dashboard shows an average actual car price of approximately 385.07K and an average absolute prediction error of approximately 112.54K for the analyzed data.


📈 Data Visualizations

The project contains visualizations for:
1.Selling Price Distribution
2.Price vs Car Age
3.Price vs Kilometers Driven
4.Actual vs Predicted Prices
5.Prediction Error by Car Age

📊 Power BI Dashboard

An interactive Power BI dashboard was created to analyze:
1.Average Actual Car Price
2.Average Prediction Error
3.Actual vs Predicted Car Prices
4.Average Prediction Error by Car Age
5.KM Driven vs Actual Selling Price
6.Car Age vs Actual Selling Price

The dashboard also includes slicers for:
1.Car Age
2.KM Driven

🔮 Future Improvements
1.Hyperparameter tuning for better model performance.
2.Compare Random Forest with other regression algorithms.
3.Deploy the model as a web application.
4.Add more real-world car features.
5.Improve prediction accuracy using advanced ensemble techniques.

 📊 Model Evaluation

The final Random Forest Regression model was evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.

| Metric | Result |
|---|---:|
| MAE | 112,539.63 |
| RMSE | 163,626.69 |
| R² Score | 0.5379 |

The Random Forest model after outlier treatment was selected as the final model based on its prediction performance.


👨‍💻 Author

**Vishal**

Machine Learning / Data Science Project