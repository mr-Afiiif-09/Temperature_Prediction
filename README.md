# Temperature Prediction Using Linear Regression

This project is part of my machine learning internship coursework. It demonstrates a complete data analysis and regression workflow to predict environmental temperature based on humidity sensor measurements using Python and Scikit-learn.

## 📂 Project Structure
```text
Weather_Prediction/
│
├── Temperature_Prediction.ipynb    # Jupyter Notebook containing the analysis, model, and evaluations
├── humidity.csv                    # Dataset used for training and testing
└── README.md                       # Project documentation

📋 Table of Contents:

1.Problem Statement
2.Objectives & Scope
3.Dataset Details
4.Methodology & Workflow
5.Results & Performance Metrics
6.Hardware & Software Requirements
7.Technologies & Libraries Used
8.Future Enhancements

**Problem Statement**
The objective of this assignment was to predict temperature based on humidity sensor measurements. The dataset contains environmental variables including sensor ID, latitude, longitude, pressure, temperature, and humidity.

**Objectives & Scope**
Objectives:
o Understand the workflow of solving a machine learning problem using a given dataset.
o Perform exploratory data analysis (EDA) and inspect statistical properties.
o Identify relevant input features and target variables.
o Apply data-cleaning and preprocessing techniques (such as handling missing values).
o Implement Linear Regression for temperature prediction.
o Split datasets into training and testing subsets (80/20 split).
o Evaluate regression models using Mean Squared Error (MSE) and R² score.

Scope: The scope is limited to data analysis, preprocessing, model training, prediction, and evaluation on the supplied dataset rather than building a fully deployed real-time weather forecasting application.
**
Dataset Details**
o Source File: humidity.csvTotal
o Records: 701,548 records across 6 columns
o Missing Values: No missing values observed in the loaded structure (rows containing missing values handled via dropna() where applicable)
o Input Feature ($X$):Humidity
o Target Variable ($y$):Temperature (continuous value being predicted)

**Methodology & Workflow:**
1.Dataset Loading: Loaded the humidity dataset using Pandas.
2.Data Inspection: Inspected structure, data types, sample records, and generated descriptive statistics.
3.Exploratory Data Analysis: Visualized the relationship between humidity and temperature using scatter plots.
4.Data Preprocessing: Cleaned the data and selected humidity as the feature and temperature as the target.
5.Train-Test Split: Split the dataset into 80% training data and 20% testing data.
6.Model Training: Trained a Linear Regression model using the training subset.
7.Prediction & Evaluation: Generated predictions on the test set and evaluated performance using MSE and R² score.

**Results & Performance Metrics**
o Model Used: Linear Regression
o Mean Squared Error (MSE): 144.0848
o R² Score: 0.2570

**Hardware & Software Requirements**
o Hardware: Standard computer/laptop with minimum 4 GB RAM (8 GB recommended); no dedicated GPU required.
o Software: Python and Jupyter Notebook.

**Technologies & Libraries Used**
o Python: Core programming language
o Jupyter Notebook: Interactive execution and documentation environment
o Pandas: Dataset loading, cleaning, and tabular data analysis
o NumPy: Numerical operations
o Matplotlib & Seaborn: Data visualization and statistical plotting
o Scikit-learn: Preprocessing, Linear Regression model building, and evaluation metrics

**Future Enhancements**
Implementing polynomial regression or time-series models to better capture complex environmental patterns and improve the R² score.
