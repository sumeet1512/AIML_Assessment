# AIML_Assessment

## Overview:
This project aims to predict sourcing costs using machine learning models. The dataset consists of features such as product type, manufacturer, area code, sourcing channel, product size, and month of sourcing. Two models, Linear Regression and Random Forest Regression, were trained and evaluated.

## Dataset:

The dataset is provided in an Excel file format.
It includes columns for product type, manufacturer, area code, sourcing channel, product size, month of sourcing, and sourcing cost.

## Exploratory Data Analysis (EDA):

Time series analysis was performed on the 'Month of Sourcing' column to visualize the trend in sourcing costs over time.

## Model Training and Evaluation:

The dataset was split into training and test sets.
Two models, Linear Regression and Random Forest Regression, were trained on the training dataset.
Mean Squared Error (MSE) was used as the evaluation metric.
Both models were evaluated on the training and test datasets, with Random Forest Regression performing better on both.

## Insights:

Random Forest Regression outperformed Linear Regression on both training and test datasets, indicating better generalization.
It was chosen as the final model for accurate sourcing cost predictions.

## Conclusion:

The project successfully trained and evaluated machine learning models to predict sourcing costs.
Random Forest Regression demonstrated superior performance and was selected as the final model.

## Future Work:

Further feature engineering and model optimization could potentially improve the predictive performance.
Exploring other regression algorithms or ensemble methods could provide additional insights.
