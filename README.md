# Loan Approval Model

This project implements a machine learning model for predicting loan approval status using a Logistic Regression algorithm. It is designed 
to help financial institutions make informed decisions about loan applications based on applicant data.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Model](#model)
- [Evaluation](#evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Loan Approval Model aims to predict whether a loan application will be approved or rejected. 
It uses Logistic Regression, a popular classification technique, to analyze historical loan application data and learn patterns that distinguish approved applications from rejected ones.

## Dataset

The model was trained on a dataset containing various features about loan applicants, such as:

- Loan Id
- Number of Dependents
- Education
- self Employed
- Annual Income
- Loan Amount
- Loan Term
- Cibil score
- Residential Assets Value
- Commercial Assets Value
- Luxury Assets Value
- Bank Asset Value
- loan status



Data preprocessing steps included handling missing values, encoding categorical features, and feature scaling.

## Model

The Logistic Regression algorithm was chosen because of its effectiveness in binary classification problems (such as loan approval: Approved vs Rejected).

**Implementation steps:**
1. Data preprocessing and feature engineering
2. Splitting the data into training and testing sets
3. Training the Logistic Regression model on the training set
4. Predicting loan approval status on the test set

## Evaluation

The model’s performance was evaluated using the Accuracy Score metric, which measures the proportion of correctly predicted loan approval statuses.

**Accuracy Score:**  
`Accuracy = (Number of correct predictions) / (Total predictions)`

Additional evaluation metrics such as precision, recall, and F1-score can be added for deeper analysis.

## Installation

1. Clone the repository:
   ```bash
   https://github.com/Animichael/Loan-Approval-model.git
