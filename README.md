# Dynamic-Flight-Price-Prediction

The link fo rthe data and other similar files are uploaded here.

[Saurabhm4ra/Dynamic-Flight-Price-Prediction](https://drive.google.com/drive/folders/1vGaxCGFht-v9BTUoIiKWIoWdmJPKekXf?usp=drive_link)


## 1. Introduction

The development of a model to predict and optimize flight prices. The primary objective is to enhance pricing strategies (i.e. increase in revenue) by analyzing historical data and implementing various statistical and machine learning techniques.

## 2. Data Preprocessing

    Loading and Cleaning Data: The dataset containing historical flight prices and relevant features is loaded and cleaned. Missing values are handled appropriately.
    Feature Engineering: New features are created based on the existing data to improve the model's predictive capabilities. These features include temporal variables (like      day of the week), flight-specific attributes (e.g., airline, distance) etc (can be explored in the data given in the drive)

## 3. Exploratory Data Analysis (EDA)

    Visualizations: Several visualizations, including histograms and KDE plots, are used to explore the distribution of flight prices and other key variables.
    Correlation Analysis: The correlation between different features is analyzed to understand their relationships and influence on flight prices.

## 4. Model Development

    Model Selection: Various models such as Linear Regression, Decision Trees, and Random Forests are explored.
    Hyperparameter Tuning: The hyperparameters of the selected models are fine-tuned using grid search to enhance performance.
    Training and Testing: The models are trained on historical data and evaluated using a test set to ensure they generalize well to unseen data.

## 5. Optimization Process

    Price Optimization: The model's predictions are used to identify optimized prices. This involves comparing predicted prices with optimized ones to determine the most         profitable pricing strategy.
    Distribution Analysis: A KDE plot compares the distribution of predicted and optimized prices, highlighting the differences and potential areas for improvement.

## 6. Results and Discussion

    Model Performance: The selected model’s performance is evaluated using metrics like RMSE and R-squared.
    Optimization Outcome: The results of the optimization process are discussed, focusing on the potential increase in revenue by adopting the optimized prices.

    Revenue before optimization: 5200284.50
    Revenue after optimization: 6239057.83

    As can be seen fromm the result that the revenue is increased by 20%. So our objective of increasing the revenue with optimized predicted price is achieved.

