# House-Price-Predictor-ML
Machine Learning project for predicting house prices using EDA, preprocessing, OneHotEncoder, pipelines, and regression models like Linear Regression, Decision Tree, and Random Forest.
📌 Project Overview

This project predicts house prices based on features such as:

Bedrooms
Bathrooms
Square feet living area
Lot area
Floors
House condition
Basement area
Year built
City
and more

The project includes:

Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Preprocessing Pipelines
Model Training & Evaluation
Prediction System
🚀 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
📊 Exploratory Data Analysis (EDA)

Performed:

Average house price by city
Scatter plots (sqft_living vs price)
Correlation analysis
Outlier detection
Feature analysis
⚙️ Models Used

The following regression models were trained and compared:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
📈 Model Evaluation

Evaluation metrics used:

MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
R² Score

🏆 Random Forest Regressor achieved the best performance.

🧠 Features Used
bedrooms
bathrooms
sqft_living
sqft_lot
floors
view
condition
sqft_above
sqft_basement
yr_built
year_cat
city
🔄 Preprocessing

Used:

StandardScaler
OneHotEncoder
ColumnTransformer
Pipeline
💡 Prediction System

Built an interactive prediction system where users can enter house details and get predicted house prices.

Example:

Predicted House Price = $400589.86
📂 Project Structure
House-Price-Prediction/
│
├── clean_house_data.csv
├── eda.ipynb
├── train_model.py
├── prediction.py
├── final_model.pkl
├── requirements.txt
└── README.md
📌 Future Improvements
Improve model accuracy
Hyperparameter tuning
Flask web application
Deployment
Better outlier handling
👨‍💻 Author

Yubaraj Halder
