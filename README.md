# credit-risk-classification-challenge

## Overview

This analysis aims to assess the credit risk of loans by using logistic regression. Credit risk is evaluated to determine the likelihood of a loan defaulting, which is critical for financial institutions in decision-making processes. The project involves splitting data into training and testing sets, creating a logistic regression model with the original data, and finally, writing a credit risk analysis report based on the model's performance.

## Instructions

### Split the Data into Training and Testing Sets

1. **Read the Data:** Begin by reading the `lending_data.csv` data from the Resources folder into a Pandas DataFrame.
2. **Create Labels and Features:**
   - Extract the `loan_status` column to use as the labels set (`y`).
   - Use the remaining columns as the features DataFrame (`X`).
     - *Note:* A `loan_status` of 0 indicates a healthy loan, while a 1 indicates a high risk of defaulting.
3. **Split the Data:** Utilize `train_test_split` to divide the data into training and testing datasets.

### Create a Logistic Regression Model with the Original Data

1. **Model Fitting:** Fit a logistic regression model using the training data (`X_train` and `y_train`).
2. **Predictions:** Save predictions for the testing data labels using the testing feature data (`X_test`) and the fitted model.
3. **Evaluate Performance:** 
   - Generate and analyze a confusion matrix.
   - Print the classification report.
   - Answer: How effectively does the logistic regression model predict both 0 (healthy loan) and 1 (high-risk loan) labels?

### Write a Credit Risk Analysis Report

Compose a report summarizing the performance of the machine learning models used. The report should include:

- **Overview:** Purpose of the analysis.
- **Results:** Detail the accuracy, precision, and recall scores of the model in a bulleted list.
- **Summary:** Summarize the machine learning model results, providing a recommendation on the model's use by the company or explaining why it should not be used.



