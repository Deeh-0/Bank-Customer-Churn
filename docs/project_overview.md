# Predicting Customer Churn

**Project Overview:**

This project aims to predict customer churn for a telecommunications company. By identifying customers at risk of leaving, the company can implement targeted retention strategies.

**Problem Statement:**

Reduce customer churn by predicting which customers are likely to terminate their services.

**Target Audience:**

* Marketing team
* Customer service representatives
* Data science team

**Data Sources:**

* "customer_churn.csv" (provided by the telecommunications company)

**Data Description:**

The dataset contains customer information, including:

* `customerID`: Unique identifier for each customer.
* `Surname`: Customer's surname.
* `CreditScore`: Customer's Credit Score.
* `Geography`: Customer's Country where the bank account was opened.
*  `Gender`: Customer's gender.
*  `Age`: Customer's Age in years.
* `Tenure`: How long the customer has been with the bank, measured in years.
* `Balance`: The balance of each customer as at the time the data was extracted for prediction.
* `NumOfProducts`: Number of products customers are using.
* `HasCrCard`: Whether the customer has a credit card.
* `IsActiveMember`: Whether the customer is still an active member of the bank.
* `EstimatedSalary`: The estimated salary of the customer.
* `Exited`: Whether the customer churned (1) or not (0).

**Data Cleaning and Preprocessing:**

1.  **Encoding Categorical Variables:**
    * Used encoding for categorical features for these columns: "gender"(binary encoding) and "Geography" (one hot encoding)


**Exploratory Data Analysis (EDA):**

* Visualized the distribution of churn.
* Visualized Churn Rate by by Tenure Category.
* Visualized Churn Distribution by Gender

**Methodology:**

* **Model Selection:**
    * Used a Random Forest Classifier due to its ability to handle complex relationships and its robustness to overfitting, other models used were Logistic Regression and XGBoost.
* **Model Training:**
    * Split the data into training and testing sets (80/20 split).
*  **Feature Scaling:**
    * Scaled numerical features using StandardScaler.
* **Model Evaluation:**
    * Evaluated the model using accuracy, precision, recall, and F1-score.
    * Generated a confusion matrix and ROC curve.
* **Validation:**
    * Cross-validation was used during the Gridsearch to validate the model's robustness.
    * Retrained the XGBoost model with tuned hyperparameters using GridSearchCV.
