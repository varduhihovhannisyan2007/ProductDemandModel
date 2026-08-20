## Introduction

This project uses machine learning to predict the demand for a product based on historical sales and pricing information. The main goal is to predict Units Sold using information such as the product ID, store ID, total selling price, and original base price. Predicting demand can help businesses make better pricing and discount decisions.

## Model Features

The model uses `ID`, `Store ID`, `Total Price`, and `Base Price` to predict `Units Sold`. These features were chosen because they give information about the product, store, and its price.

## Model and Evaluation

I used a **Decision Tree Regressor** because `Units Sold` is a numerical value and the relationship between price and demand may not be linear. The dataset was split into **80% training data and 20% testing data** using `train_test_split`.

The model was evaluated using the `score()` function, which gives the **R² score** for a regression model. The model was also used to predict the units sold for the test data and compare the predictions with the actual values.

## Why This Method?

A Decision Tree was chosen because it can find patterns in the data without assuming a linear relationship. The 80/20 split was used to train the model on most of the data while keeping some data separate for testing its performance.

