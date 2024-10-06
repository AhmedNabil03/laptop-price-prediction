# Laptop Price Prediction

This project focuses on building a machine learning model to predict laptop prices based on various features. By analyzing a comprehensive dataset of laptop specifications and prices, we implemented and compared multiple regression algorithms to determine the most accurate model. The goal of this project is to develop a reliable pricing model that can be used for applications such as market analysis, pricing optimization, and budget planning.

## Dataset Overview
The dataset used for this project contains the following columns:
- Company
- TypeName
- Inches
- ScreenResolution
- Cpu
- Ram
- Memory
- Gpu
- OpSys
- Weight
- Price

## Steps Taken
### Data Preprocessing and Feature Engineering
Several steps were taken to prepare the dataset for modeling which include:
- Handling missing values and outliers.
- Resolved inconsistencies and formatted data for analysis.
- Converted columns to appropriate data types and extracted useful features from them.
- Feature scaling to normalize the data for certain algorithms.
- Conversion of categorical features into numerical values using one-hot encoding.

### Exploratory Data Analysis (EDA)
- Explored relationships between features and the target variable (Price).
- Visualized distributions, correlations, and trends in the data.

### Modeling
After splitting the dataset into training and testing sets, The following algorithms were evaluated to identify the best-performing model:
- Linear Regression
- Ridge Regression
- Lasso Regression
- KNN
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- ExtraTrees
- AdaBoost
- Gradient Boost
- XGBoost
- Stacking Regressor
- Voting Regressor

### Model Evaluation
The models were evaluated using **Mean Absolute Error (MAE)** and **R² score** to measure their accuracy and predictive power.

## Tools
- **Python**

## Conclusion
This project demonstrated the effectiveness of various regression models in predicting laptop prices. We explored multiple machine learning techniques to find the best-performing model that can be used for real-world applications such as pricing optimization, market analysis, and budget planning.
