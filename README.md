# Car Market Analysis

## Overview
This project aims to analyze the car market by exploring various factors that influence car prices. The dataset used contains information about car models, manufacturers, fuel types, years, mileage, and prices. The analysis involves data cleaning, exploratory data analysis, feature engineering, and building predictive models to determine the key drivers of car prices.

## Data Preprocessing
1. The dataset was loaded and initial checks were performed to understand the structure and contents.
2. Columns with irrelevant information were dropped, and duplicates were removed.
3. Categorical variables were encoded, and numerical variables were scaled for the machine learning models.

## Exploratory Data Analysis
1. The most popular car models, manufacturers, and fuel types were analyzed.
2. The average prices, mileage, and engine volume for different car attributes were explored.
3. Correlations between the features and price were investigated.
4. Distributions of the key variables, such as year, mileage, and engine volume, were visualized.
5. The relationship between mileage, engine volume, and price was analyzed through scatter plots.
6. The impact of fuel type and manufacturer on prices was examined.
7. Regional differences in car prices and popularity were investigated.

## Feature Engineering
1. The relevant features for the predictive models were selected, including mark (manufacturer), year, mileage, and engine volume.
2. The target variable was the car price.

## Model Building and Evaluation
1. Several regression models were trained, including Linear Regression, Support Vector Regressor, Random Forest Regressor, AdaBoost Regressor, Gradient Boosting Regressor, and XGBoost Regressor.
2. The models were evaluated using metrics such as Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, and R-squared.
3. The best-performing model was the Random Forest Regressor, with an R-squared of 0.88.

## Key Findings
<img width="1186" alt="Screenshot 2024-12-07 at 17 18 32" src="https://github.com/user-attachments/assets/9cc5ff3a-8e9b-40cd-ab34-7f72cb8bab74">
1. Fuel efficiency (fuel) is the most important feature in determining car prices, followed by engine volume (vol_engine) and mileage (mileage).
2. Electric and hybrid vehicles tend to have the highest average prices, while CNG and LPG-powered vehicles have the lowest.
3. The top car manufacturers in terms of average prices are Mercedes-Benz, BMW, and Audi.
4. Certain regions, such as Niedersachsen and Moravian-Silesian Region, have higher average car prices compared to other provinces.
5. The most popular car models in the market are Opel Astra, BMW Serie 3, and Audi A4.

## Conclusion
This comprehensive analysis of the car market provides valuable insights for manufacturers, dealers, and consumers. The findings can help guide strategic decisions around product development, pricing, and marketing to better meet customer preferences and remain competitive in the industry. The predictive models developed can also be used to estimate car prices based on their attributes.

Future work could involve incorporating additional data sources, such as customer reviews and economic indicators, to further enhance the analysis and model performance.
