<p align="center"><img src="https://socialify.git.ci/navyadua/Bank-Fraud-Detection/image?font=Inter&name=1&theme=Light" alt="project-image"></p>

# Bank Fraud Detection

This project focuses on building a robust machine learning model for detecting potentially fraudulent transactions using advanced techniques in machine learning and predictive analytics. The dataset encompasses various transaction details such as account age, payment method, transaction time, and category. The objective is to construct a classification model capable of accurately categorizing transactions as either legitimate or potentially fraudulent.

## Problem Statement
Develop a machine learning model capable of detecting potentially fraudulent transactions based on the provided dataset's features. The classification model aims to distinguish between legitimate and suspicious transactions.

## Data Description
The dataset includes the following features:

- `accountAgeDays`: Number of days the account has been active.
- `numitems`: Number of items associated with the account.
- `localTime`: Time of transaction in hours or a similar unit.
- `paymentMethod`: Method used for payment (e.g., PayPal, store credit, credit card).
- `paymentMethodAgeDays`: Number of days since the payment method was associated with the account.
- `isWeekend`: Binary indicator (1 for yes, 0 for no) if the transaction occurred on a weekend.
- `Category`: Category of the transaction (e.g., electronics, shopping, food).
- `Label` (Target column): Binary label (0 for legitimate, 1 for potentially fraudulent).

## Process

- **Data Exploration**: Initial examination of the dataset to understand its structure, features, and statistical properties.
- **Data Cleaning**: Handling missing values and ensuring data quality.
- **Label Encoding**: Converting categorical variables into numerical format using label encoding.
- **Feature Engineering**
- **Data Visualization**
- **Model Selection** : Random Forest Classifier is Chosen for its ability to handle complex relationships in data, robustness, and effectiveness in classification tasks.
- **Model Training** : GridSearchCV is Employed for hyperparameter tuning to find the best combination of parameters for the Random Forest Classifier.
- **Model Evaluation** : Accuracy, Precision, Recall, F1 Score are used to assess the model's performance on the test set and Confusion Matrix is used for providing a detailed breakdown of the model's predictions.

##

Thank You for checking out our project!😉 We believe in creating a better world through technology⚙️, and we hope this project contributes to that goal.👍🏻
