
📌 Analysis and Prediction of Airbnb Listing Prices  
🔍 Project Overview  
This project analyzes and predicts Airbnb listing prices in New York City using *Exploratory Data Analysis (EDA)* and *Machine Learning models. The objective is to uncover key factors influencing listing prices and build predictive models using **Linear Regression* and *Random Forest* in R.  

📌 Project Workflow  
1. Data Import & Cleaning  
   - Remove missing values & redundant columns  
   - Handle outliers using the *Interquartile Range (IQR) 

2. Exploratory Data Analysis (EDA)  
   - Correlation analysis  
   - Histograms, scatter plots, and boxplots  

3. Feature Engineering  
   - Distance from *Times Square 
   - Days since the last review  
   - Review rate per month  
   - Encoding categorical variables  

4. Modeling & Evaluation  
   - Linear Regression  
   - Random Forest Regression  
   - Performance evaluation using RMSE  

## 📌 Technologies Used  
🔹 R Programming (tidyverse, ggplot2, randomForest, caTools, dplyr)  
🔹 Data Visualization (ggplot2, corrplot)  
🔹 Machine Learning (Linear Regression, Random Forest)  

## 📌 Dataset  
📍 Source: [Kaggle: NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data/data)  

## 📌 Results  
📌 The Random Forest model outperformed Linear Regression with a lower RMSE, making it a better choice for price prediction.  

## 📌 How to Use  
1. Clone the repository:  
   bash
   git clone https://github.com/your-username/airbnb-price-prediction.git
   cd airbnb-price-prediction
   
2. Open the R scripts and execute them in order:  
   - data_cleaning.R  
   - eda_visualizations.R  
   - feature_engineering.R  
   - modeling.R  

📌 Contributors  
👤 Jithendranath Reddy Keshavareddy  
📅 Date: 10/07/2024  
