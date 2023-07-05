# House-Sales-Prices-Analysis-Using-Multi-Linear-Regression
![HouseImage](images/Stock-TraditionalNeighborhood-AdobeStock-180147418-copy.jpeg)

# Introduction
The goal of this project is to analyze house sales data using multiple regression modelling techniques. By employing multiple regression, we aim to identify and quantify the relationships that exists between various factors or predictors and house sale prices.This analysis will provide insights into the key drivers of house prices and help shareholders make informed decisions related to real estate investment.

# Problem Statement
This project seek to address the importannce of identifying the factors that significantly affect house prices.Traditional approaches often rely on anectodal evidence or limited analysis, resulting into inaccurate insights. This knowledge gap hampers stakeholders' ability to predict and interpret house proce flactuations effectively. To address this problem, we propose utilizing multiple regression modeling techniques to analyze house sales data comprehensively. By conducting multiple regression, we can identify the relationship between different factors and house sales prices, taking into account the collective impact of multiple independent variables.

# Main Objective
To analyze house sales data using multiple regression modeling techniques to identify and quantify the key factors influencing house sales prices and help shareholders make data driven decisions on investing in real estate.

# Specific Objectives

1. Conduct explanatory data analysis to gain insights on the relationships between different variables and target variable, assisting in selection of relevant variables for regression model.
2. Develop multiple regression model to predict house sale prices, considering the selected independent variables and their impact on the dependent variable.Validate the model assumptions, assess its goodness of fit and refine the model if necesssay.
3. Interpret the coefficients of the independent variables in the model to determine their individual impact on house prices, identifying the most influential factors driving thr house sales prices and their respective effects.
4. Evaluate and validate the performnance of the model.
5. Provide actionable insights and recommendations based on the analysis to assist real estate investors, and policymakers in making informed decisions regarding property investment, market trends, and economic planning.

# Notebook Structure
1. Reading the data.
2. Data Cleaning and Preprocessing.
3. Multiple Regression Modelling.
4. Model Evaluation and Undesrtanding.
5. Results Presentation and Conclusions.
6. Recommendations
7. References.

# Business Understanding
 Real estate agents can benefit from the regression analysis by understanding the factors that influence house prices. They can utilize the regression model to provide more accurate price estimates to their clients, identify key features to highlight in property listings, and make informed recommendations to buyers and sellers. We could also consider Homeowners and sellers who can use the regression model to estimate the potential value of their properties. By considering the influential features identified in the regression analysis, they can assess the impact of certain improvements or renovations on the property's price and make informed decisions regarding pricing and marketing strategies.

# Data Understanding
The dataset used in this project contains information about the factors affecting the housing prices including variables such as date, sqft_above, view and sqft_basement. Explanatory data analysis will be used to get a clear understanding of the dataset including the missing values, checking the data types, identifying outliers and also extracting relevant features for analysis. 

# Methodology
The methodology provides a structured approach to conduct the analysis using multiple regression modeling.It ensures appropriate handling of data, selection of relevant variables,model development, and validation to achieve accurate and reliable insights into the factors impacting house sale prices.

# Results & Interpretation
## Regression Model

## Regression Model
House Price = β0 + β1 * bedrooms + β2 * bathrooms + β3 * sqft_living + β4 * sqft_lot + β5 * floors + β6 * grade + β7 * sqft_above + β8 * yr_built + β9 * lat + β10 * long

In this project, we developed a multiple linear regression model to predict house sale prices based on various independent variables. The model was trained using the scikit-learn library and applied to the house sales dataset.

The main independent variables included in the model were: sqft_living, bedrooms, bathrooms, location, amenities, and property grade. Before fitting the model, we performed data cleaning and preprocessing steps to handle missing values, outliers, and feature scaling.

The model achieved a train score of 0.769 and a test score of 0.762, indicating a good fit to the data and reasonable predictive performance. The mean absolute error (MAE) on the test set was 0.085, the root mean squared error (RMSE) was 0.110, and the mean squared error (MSE) was 0.012.

The regression coefficients of the independent variables in the model provide insights into their impact on house prices. The coefficient values can be interpreted as follows:
- Feature 1: -0.004 - This indicates that a one-unit decrease in feature 1 results in a decrease of 0.004 in the predicted house price.
- Feature 2: 0.023 - A one-unit increase in feature 2 leads to an increase of 0.023 in the predicted house price.
- Feature 3: 0.027 - A one-unit increase in feature 3 contributes to a 0.027 increase in the predicted house price.
...

Overall, the regression analysis identified several significant factors influencing house sale prices, including property size, location, amenities, and property grade. These insights can be used by real estate agents, homeowners, and policymakers to make informed decisions regarding property investments, pricing strategies, and market trends.


# Recommendations & Conclusions
1. Feature Enhancement: Consider enhancing or upgrading the features that positively affect house prices. For example, increasing the square footage of the living area, improving the overall grade of the property, or adding more bathrooms can potentially increase the value of the house.
2. Feature Importance: Analyze the regression coefficients to identify the most influential features on house prices. Focus on the features with higher coefficients, such as 'sqft_living', 'grade', 'bathrooms', and 'sqft_above', as they have a stronger impact on the predicted prices.
3. Price Prediction: Utilize the regression model to predict house prices based on the given set of independent variables. This can be useful for estimating the selling price of houses or determining the potential value of a property.
4. Data Collection: Consider collecting additional relevant data that could improve the accuracy of the regression model. This may include variables such as location-specific factors, proximity to amenities, property age, or neighborhood characteristics.
5. Market Segmentation: Analyze the relationship between the independent variables and house prices to identify market segments or specific buyer preferences. For instance, if higher-grade houses tend to have higher prices, it may indicate a market segment of luxury or high-end properties.
6. Further Analysis: Perform additional exploratory data analysis and feature engineering to uncover additional patterns and insights. Consider examining correlations, visualizing distributions, or conducting hypothesis testing to deepen the understanding of the data.
7. Model Evaluation: Continuously evaluate and monitor the performance of the regression model. Assess the R-squared values, MAE, RMSE, and MSE to gauge the model's predictive accuracy and potential areas of improvement