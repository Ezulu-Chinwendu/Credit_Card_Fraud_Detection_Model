# Credit Card Fraud Prediction Using Logistic Regression Model

### Overview

This project aims to build a machine learning model to predict fraudulent credit card transactions using logistic regression. Given the rise in digital payments and cyber crimes, detecting fraud is crucial. This project addresses the challenge of imbalanced datasets, where fraudulent transactions are significantly less common than legitimate ones. By leveraging logistic regression, the project evaluates the model's performance and applies techniques to improve predictions on rare fraudulent transactions.

### Dataset
The dataset used in this project is available for download at (https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud.)

Features:
distance_from_home: Distance from the account owner's home to where the transaction occurred.
distance_from_last_transaction: Distance from the last transaction.
ratio_to_median_purchase_price: Ratio of the transaction price to the median purchase price.
repeat_retailer: Indicates if the transaction occurred at the same retailer.
used_chip: Indicates if the transaction used a chip card.
used_pin_number: Indicates if the transaction required a PIN number.
online_order: Indicates if the transaction was made online.
fraud: Indicates if the transaction is fraudulent.

### Model Development
The primary challenge in building the fraud detection model is the imbalance in the dataset, with only 8.74% of transactions being fraudulent. Logistic regression is used to model and predict fraudulent transactions. Performance evaluation and techniques to handle the rare class problem are applied to improve the model's effectiveness.


### Usage
Download the dataset from the link provided.
Load the dataset and preprocess it as specified in the project.
Use the logistic regression model and scaler to make predictions on new data.


### Contribution
Feel free to contribute to the project by opening issues or submitting pull requests. For any questions or suggestions, please contact me @ ezuluchinwe1@gmail.com.









