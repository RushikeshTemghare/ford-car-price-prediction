Ford Car Price Prediction using Linear Regression

Predicting used Ford vehicle prices using a Linear Regression model built with Python and Scikit-learn.

🐍 Python • 🤖 Scikit-learn • 📓 Jupyter Notebook • 📊 Machine Learning • ✅ Status: Completed • 📄 MIT License

📖 Project Overview

This project demonstrates the implementation of a supervised Machine Learning regression model to predict the selling prices of used Ford vehicles using Linear Regression.

The project follows a complete end-to-end machine learning workflow, including:

Data loading
Exploratory Data Analysis (EDA)
Data preprocessing
Feature encoding
Model training
Model prediction
Model evaluation

The model was developed using Python and Scikit-learn to understand how various vehicle characteristics influence resale prices.

🎯 Problem Statement

The selling price of a used Ford vehicle depends on several factors, including:

Vehicle model
Manufacturing year
Mileage
Transmission type
Fuel type
Engine size
Road tax
Fuel efficiency (MPG)

The objective of this project is to build a regression model capable of predicting the market value of a used Ford vehicle based on these attributes.

📊 Dataset

The dataset contains historical information about used Ford vehicles.

Feature	Description
model	Ford vehicle model
year	Manufacturing year
price	Selling price (Target Variable)
transmission	Transmission type
mileage	Vehicle mileage
fuelType	Fuel type
tax	Vehicle road tax
mpg	Miles per gallon
engineSize	Engine size (litres)

🛠️ Technologies Used
🐍 Python
📓 Jupyter Notebook
🐼 Pandas
🔢 NumPy
📊 Matplotlib
📈 Seaborn
🤖 Scikit-learn

⚙️ Machine Learning Workflow
Import Libraries
Load Dataset
Exploratory Data Analysis (EDA)
Data Cleaning
Feature Encoding
Feature Selection
Train-Test Split
Linear Regression Model Training
Model Prediction
Model Evaluation

📈 Model Evaluation

The trained Linear Regression model was evaluated using the following regression metrics:

Metric	Value
Mean Absolute Error (MAE)	1764.68
Mean Squared Error (MSE)	6,096,685.95
Root Mean Squared Error (RMSE)	2469.15
R² Score	0.731

📊 Results
Key Findings
The Linear Regression model achieved an R² Score of 0.731.
The model explains approximately 73.1% of the variance in used Ford vehicle prices.
Features such as model, mileage, manufacturing year, engine size, and fuel type significantly influence vehicle prices.
The notebook includes predictions on unseen test data along with evaluation metrics to assess model performance.

💡 Skills Demonstrated
Data Cleaning
Data Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Feature Encoding
Feature Selection
Supervised Machine Learning
Regression Analysis
Linear Regression
Model Evaluation
Python Programming

🚀 Future Improvements

Possible enhancements for this project include:

Ridge Regression
Lasso Regression
Decision Tree Regression
Random Forest Regression
Gradient Boosting Regression
XGBoost Regression
Hyperparameter Tuning
Cross Validation
Feature Scaling Comparison

📚 Learning Outcomes

Through this project, I gained practical experience in:

Building an end-to-end machine learning regression pipeline
Performing Exploratory Data Analysis (EDA)
Preparing real-world datasets for modelling
Encoding categorical variables for machine learning
Training and evaluating Linear Regression models
Interpreting regression performance metrics
Predicting continuous numerical values using supervised learning

👤 Author

Rushikesh Temghare

MSc Data Science & Artificial Intelligence
Bournemouth University
