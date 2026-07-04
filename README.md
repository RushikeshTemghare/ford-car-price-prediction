# Ford Car Price Prediction using Linear Regression

Predicting used Ford vehicle prices using a Linear Regression model built with Python and Scikit-learn.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange?logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📖 Project Overview

This project demonstrates the implementation of a **Supervised Machine Learning** model to predict the selling prices of used Ford vehicles using **Linear Regression**.

The project follows a complete end-to-end machine learning workflow, including data preprocessing, feature encoding, model training, prediction, and performance evaluation using **Python** and **Scikit-learn**.

The objective is to understand how different vehicle characteristics influence resale prices and build a regression model capable of estimating the market value of a used Ford vehicle.

---

# 🎯 Problem Statement

The selling price of a used Ford vehicle depends on several factors, including:

- Vehicle Model
- Manufacturing Year
- Mileage
- Transmission Type
- Fuel Type
- Engine Size
- Road Tax
- Fuel Efficiency (MPG)

The objective of this project is to predict the selling price of a used Ford vehicle based on these features using a Linear Regression model.

---

# 📊 Dataset

The dataset contains historical information about used Ford vehicles.

| Feature | Description |
|----------|-------------|
| model | Ford vehicle model |
| year | Manufacturing year |
| price | Selling price (Target Variable) |
| transmission | Transmission type |
| mileage | Vehicle mileage |
| fuelType | Fuel type |
| tax | Annual road tax |
| mpg | Miles per gallon |
| engineSize | Engine size (litres) |

---

# 🛠️ Technologies Used

- 🐍 Python
- 📓 Jupyter Notebook
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 📈 Seaborn
- 🤖 Scikit-learn

---

# ⚙️ Machine Learning Workflow

- Import Libraries
- Load Dataset
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Encoding
- Feature Selection
- Train-Test Split
- Linear Regression Model Training
- Model Prediction
- Model Evaluation

---

# 📈 Model Evaluation

The trained Linear Regression model was evaluated using multiple regression performance metrics.

| Metric | Value |
|---------|-------:|
| Mean Absolute Error (MAE) | **1764.68** |
| Mean Squared Error (MSE) | **6,096,685.95** |
| Root Mean Squared Error (RMSE) | **2469.15** |
| R² Score | **0.731** |

---

# 📊 Results

### Key Findings

- The model achieved an **R² Score of 0.731**, explaining approximately **73.1%** of the variance in used Ford vehicle prices.
- Vehicle characteristics such as **model, mileage, manufacturing year, engine size, transmission type, and fuel type** contribute significantly to predicting resale prices.
- The trained model provides reasonably accurate predictions on unseen test data.
- Model performance was evaluated using MAE, MSE, RMSE, and R² Score.

---

# 💡 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Encoding
- Feature Selection
- Supervised Machine Learning
- Regression Analysis
- Linear Regression
- Model Evaluation
- Python Programming

---

# 🚀 Future Improvements

Possible enhancements for this project include:

- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost Regression
- Hyperparameter Tuning
- Cross Validation
- Feature Scaling
- Model Comparison

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Building an end-to-end supervised machine learning workflow
- Performing Exploratory Data Analysis (EDA)
- Preparing real-world datasets for modelling
- Encoding categorical variables for regression models
- Training and evaluating Linear Regression models
- Interpreting regression performance metrics
- Predicting continuous numerical values using supervised learning

---

# 👤 Author

**Rushikesh Temghare**

MSc Data Science & Artificial Intelligence  
Bournemouth University

---

# 📄 License

This project is licensed under the **MIT License**.
