# data-internship-log

This repository serves as a personal record of my internship journey, showcasing the projects, analyses, and insights I gained during the experience.

## Week 1: Glassdoor Salary Prediction
This project analyzes Glassdoor job postings (2017-2018) to predict tech salaries and uncover compensation trends. Using features like job titles, company size, location, and required skills, we:  

- Cleaned/processed data to extract salary estimates, company age, and skill requirements  
- Engineered features
- Applied Textual Data Preprocessing
- Built regression models (Linear Regression, Random Forest, XGBoost)  
- Identified Python proficiency (+$8K salary premium) and company size as key drivers  

## Week 2: Amazon Prime Video Content Analysis
This project analyzes Amazon Prime Video's content library to predict IMDb scores and optimize content strategy. Leveraging data on titles, genres, directors, and release years, we:

- Conducted Exploratory Data Analysis (EDA) to understand content distribution and genre trends.
- Engineered relevant features and handled missing data.
- Built regression models (Random Forest, XGBoost) to predict IMDb scores.
- Developed a classification model (Random Forest) to distinguish movies from shows.
- Utilized SHAP values to interpret model predictions and identify key drivers.
- Identified director popularity and genre (drama) as significant predictors of high IMDb scores, and runtime as a key factor in content  preference.

## Week 3: Yes Bank Stock Price Analysis & Prediction
This project analyzes Yes Bank’s historical stock data (2005–2020) to predict monthly closing prices and understand volatility drivers. Key steps included:

- Conducted Exploratory Data Analysis (EDA) to identify trends, including the 2018 fraud-driven collapse (95% drop) and COVID-19 impact (all-time low of ₹5.55).
- Engineered relevant features with lag variables, moving averages, and volatility metrics to capture temporal patterns.
- Built regression models using ARIMA (R²=0.78), Linear Regression (R²=0.91), and XGBoost (R²=0.98), with SHAP values highlighting Low price as the top predictor.
- Performed Volatility Analysis via box plots and autocorrelation, revealing crisis-driven outliers and short-term price dependencies.
- Integrated Azure for AutoML-driven hyperparameter tuning and model deployment.
- Identified pre-2018 growth as unsustainable, with post-crisis recovery hindered by pandemic shocks.
- Demonstrated that technical indicators (6-month MA, Bollinger Bands) improve crisis prediction accuracy.
- Recommended combining XGBoost with real-time sentiment analysis for adaptive forecasting in volatile markets.

## Week 3: Flipkart Customer Satisfaction Analysis
- Conducted Exploratory Data Analysis (EDA) to understand trends in CSAT scores, analyzing product categories, handling time, agent shifts, and customer issue types affecting satisfaction.
- Engineered relevant features by encoding categorical variables, handling missing values, and scaling numerical attributes to improve model performance.
- Built and evaluated multiple ML models, including Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM), selecting Random Forest as the best model due to its superior accuracy and generalizability.
- Performed Hyperparameter Tuning using GridSearchCV, optimizing model parameters for better predictive performance.
- Applied SHAP for Model Explainability, identifying handling time, order issues, and product categories as the most influential factors in predicting CSAT scores.
- Demonstrated business impact, showing how predictive insights help optimize customer service, reduce dissatisfaction, and enhance operational efficiency.
- Recommended integrating real-time sentiment analysis and deploying the model for automated CSAT predictions, enabling proactive service improvements at Flipkart.

## Week 4: MediBuddy Insurance Analytics & Prediction

- Analyzed MediBuddy’s insurance dataset to understand how factors like gender, region, BMI, age, smoking status, and number of children influence insurance charges.  
- Performed data cleaning, merging, and exploratory data analysis (EDA) using visualizations and group-wise aggregations to uncover patterns and cost differences across demographics.  
- Key findings included: smokers pay ~3.8x more than non-smokers; higher BMI is associated with increased charges; and men, on average, incur ~11% more charges than women.  
- Built and evaluated two machine learning models—**Linear Regression** and **Random Forest Regressor**—to predict medical insurance charges.  
- Selected **Random Forest** for final deployment due to its better accuracy and ability to capture non-linear patterns, with performance validated using RMSE and R² scores.  
- Recommended using BMI and smoking status as key criteria for dynamic pricing and discount strategies to personalize policy premiums and improve risk assessment.

## Week 5: Airbnb Product Dissection and Schema Design  
- Conducted an in-depth analysis of Airbnb’s platform to understand how it solves real-world problems in the travel and lodging industry, including affordability, trust, and cultural authenticity.  
- Identified key features such as verified user profiles, diverse property listings, secure payments, and advanced filtering that enhance user experience and operational efficiency.  
- Designed a detailed database schema covering core entities like Users, Listings, Bookings, Reviews, Payments, and Messages, ensuring support for all major platform functionalities.  
- Created a comprehensive ER diagram using PlantUML to visually represent entity relationships and enforce data integrity.  
- Highlighted Airbnb’s user-centric design philosophy and scalable data architecture, showcasing how schema structure supports personalized, seamless booking experiences.