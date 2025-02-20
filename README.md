# Customer Churn Prediction

This repository contains the code and documentation for a project aimed at predicting customer churn for a telecommunications company, using machine learning techniques.

## Project Overview

The goal of this project is to develop a predictive model that can identify customers at risk of churning (leaving the company). By accurately predicting churn, the company can implement targeted retention strategies to reduce customer attrition.

## Files and Directories

* **`README.md`**: This file, providing an overview of the project.
* **`data/`**: Contains the dataset used in this project.
    * **`data/Bank Churn.csv`**: The original dataset.
* **`notebooks/`**: Jupyter Notebooks used for exploratory data analysis (EDA) and model development.
    * `churn_prediction.ipynb`: The main notebook for the churn prediction workflow.
* **`figures/`**: Contains generated reports, visualizations, and figures.
* **`requirements.txt`**: Lists the Python libraries required to run the project.


### Usage

1.  Open and run the Jupyter Notebook `notebooks/churn_prediction.ipynb` to execute the project workflow.

### Data

The dataset used in this project is `Bank Churn.csv`, provided by the telecommunications company. The raw data is located in `data/`.

### Methodology

A Random Forest Classifier was one of the models used to predict customer churn. The data was preprocessed, and the model was trained and evaluated using appropriate metrics. Detailed information can be found within the `notebooks/churn_prediction.ipynb` file and inside the `docs/` folder.

### Results

The model achieved an accuracy of approximately 86% on the test set. Key features influencing churn were identified.

### Collaborators

* Charles Ejete - Collaboratoe - https://github.com/Olisa123456

### Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues.

