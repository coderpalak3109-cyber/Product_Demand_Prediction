# Product_Demand_Prediction
Data Analytics Project


A Machine Learning project that predicts product demand using historical sales data. The project uses **Linear Regression** to identify relationships between different factors and product demand, helping businesses make better inventory and sales-planning decisions.

## 📌 Project Overview

Accurate demand prediction is important for businesses because it helps them:

* Maintain appropriate inventory levels
* Reduce overstocking and wastage
* Avoid product shortages
* Improve purchasing and production planning
* Make data-driven business decisions

In this project, historical food/product demand data is analyzed and a **Linear Regression model** is trained to predict demand.

## 🎯 Objectives

* Analyze historical product demand data
* Perform data preprocessing and exploratory data analysis
* Identify important factors affecting demand
* Train a Linear Regression model
* Predict future product demand
* Evaluate the performance of the model

## 🗂️ Dataset

The project uses the **Food Demand Forecasting Dataset**.

The dataset contains historical information related to food orders and demand. It can be used to understand patterns in demand and build a predictive model.

### Important information in the dataset may include:

* Product/Meal information
* Center information
* Week
* Checkout price
* Base price
* Promotional information
* Number of orders/demand

## 🤖 Machine Learning Model

### Linear Regression

**Linear Regression** was used as the primary prediction model.

The model attempts to establish a relationship between the input features and the target variable (product demand).

The general form of Linear Regression is:

**y = β₀ + β₁x₁ + β₂x₂ + ... + βₙxₙ**

Where:

* `y` = predicted product demand
* `β₀` = intercept
* `β₁ ... βₙ` = model coefficients
* `x₁ ... xₙ` = input features

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Linear Regression Model
   ↓
Model Training
   ↓
Demand Prediction
   ↓
Model Evaluation
```

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Exploratory data visualization
* **Scikit-learn** – Machine Learning
* **Jupyter Notebook / Google Colab** – Development environment

## 📈 Model Evaluation

The Linear Regression model can be evaluated using metrics such as:

* **Mean Absolute Error (MAE)** – Measures the average absolute difference between actual and predicted demand.
* **Mean Squared Error (MSE)** – Measures the average squared prediction error.
* **Root Mean Squared Error (RMSE)** – Represents the typical magnitude of prediction errors.
* **R² Score** – Measures how well the model explains the variation in demand.

## 💡 Key Learning Outcomes

Through this project, I learned:

* How to work with a real-world dataset
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature selection
* Splitting data into training and testing sets
* Implementing Linear Regression using Scikit-learn
* Evaluating a Machine Learning model
* Understanding the relationship between features and product demand

## 🚀 Future Scope

The project can be further improved by:

* Comparing Linear Regression with advanced ML models
* Using time-series forecasting techniques
* Adding more historical data
* Incorporating seasonal and promotional trends
* Building an interactive demand prediction dashboard
* Integrating the model with inventory-management systems
* Connecting the prediction system with a **Smart Dustbin / IoT-based inventory monitoring system** for real-time stock-level monitoring

## 📁 Project Structure

```text
Product-Demand-Prediction/
│
├── dataset/
│   └── food_demand.csv
│
├── Product_Demand_Prediction.ipynb
│
├── README.md
│
└── requirements.txt
```

## ⚙️ Installation

Clone the repository:

```bash
git clone <your-repository-link>
cd Product-Demand-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

## 👩‍💻 Author

**Palak Soni**
**Abhishek Dewangan**
**Abhinav Walde**
**Shruti Sahu**

B.Tech – Computer Science Engineering
National Institute of Technology Raipur

## ⭐ Conclusion

This project demonstrates how **Machine Learning and Linear Regression** can be applied to historical demand data to predict future product demand. Such predictive systems can help businesses optimize inventory, reduce wastage, and make more informed decisions.

