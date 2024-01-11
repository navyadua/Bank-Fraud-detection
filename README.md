<p align="center"><img src="https://socialify.git.ci/navyadua/Bank-Fraud-Detection/image?font=Inter&name=1&theme=Light" alt="project-image"></p>

# Fraud Detection

## Description

This repository contains the code and resources for a machine learning project focused on detecting fraudulent transactions using advanced techniques.

## Project Overview

The aim of this project was to build a classification model to distinguish potentially fraudulent transactions from legitimate ones based on various transaction features.

### Problem Statement

Develop a machine learning model that accurately classifies transactions as either legitimate or potentially fraudulent using provided transaction data.

### Data Details

The dataset includes the following features:

- `accountAgeDays`: Number of days the account has been active.
- `numitems`: Number of items associated with the account.
- `localTime`: Time of transaction in hours or a similar unit.
- `paymentMethod`: Method used for payment (e.g., PayPal, store credit, credit card).
- `paymentMethodAgeDays`: Number of days since the payment method was associated with the account.
- `isWeekend`: Binary indicator (1 for yes, 0 for no) if the transaction occurred on a weekend.
- `Category`: Category of the transaction (e.g., electronics, shopping, food).
- `Label` (Target column): Binary label (0 for legitimate, 1 for potentially fraudulent).

### Model Used

K-Nearest Neighbors (KNN) Classification Algorithm


## Acknowledgments

Special thanks to Learnbay for providing the project guidelines and resources.
