# Bike Rentals Prediction Project
> This project aims to predict the number of bike rentals based on environmental factors and time-related variables. By analyzing these factors, I attempt to identify trends and patterns to improve forecasting accuracy.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Background**:  
  The dataset used in this project is related to bike rental data, which includes information such as temperature, humidity, wind speed, and time-related columns. The goal of the project is to predict the number of bike rentals (`cnt`) based on these factors. This prediction can be useful for companies in the bike rental industry to optimize fleet management and improve forecasting.

- **Business Problem**:  
  The bike rental company aims to better forecast the demand for bikes. Accurate forecasting can help them ensure that they have an adequate number of bikes available, reducing understocking or overstocking issues. By predicting rentals based on environmental and temporal factors, the company can optimize its operations.

- **Dataset**:  
  The dataset, `day.csv`, contains data on bike rentals from a bike-sharing company. It includes both numerical features like temperature and wind speed, as well as categorical features like the day of the week and season. The target variable in this dataset is `cnt` (the number of bike rentals), and the goal is to build a predictive model using these features.

## Conclusions
- **Correlation Analysis**:  
  I observed that weather conditions such as temperature (`temp`) and apparent temperature (`atemp`) had a significant positive correlation with bike rentals. Higher temperatures generally led to more rentals, as expected.
  
- **Data Preprocessing**:  
  The dataset required handling missing values and irrelevant columns (such as `instant`, `dteday`, `casual`, and `registered`), which were dropped. The categorical variables were converted to the category type and one-hot encoded, enabling them to be used in machine learning models.

- **Model Performance**:  
  The Linear Regression model showed reasonable performance, with an R-squared value of around `X.XX`. The Mean Absolute Error (MAE) was found to be relatively low, but there is still room for improvement with more complex models or feature engineering.

- **Residuals Analysis**:  
  After evaluating the residuals, the analysis revealed that the model's predictions were fairly unbiased. However, further model improvements (e.g., using polynomial regression or ensemble methods) could improve the accuracy of predictions.

## Technologies Used
- **pandas** - version 1.2.3  
- **numpy** - version 1.19.2  
- **matplotlib** - version 3.3.4  
- **seaborn** - version 0.11.1  
- **scikit-learn** - version 0.24.1  

## Acknowledgements
- The dataset used in this project was given by Upgrad.com.

## Contact
Created by https://github.com/mayurajain - feel free to contact me!

