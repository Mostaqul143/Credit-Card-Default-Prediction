# Credit-Card-Default_Prediction

Welcome to my Credit Card Fraud Detection project! This repository contains the analysis of the credit card fraud detection dataset. The analysis aims to predict fraudulent transactions in credit card data.

## Features

- Visualizations of transaction details such as amount, merchant, and transaction time.
- Comparative analysis of fraudulent transactions across different days and months.
- Breakdown of fraudulent transactions by various features.
- Trends in fraudulent transactions over time.

## Dataset:
The dataset used for the analysis contains information on various features such as Sex, Marriage, Education, and Age, among others. It also includes the target variable, which indicates whether the credit card holder defaulted or not.

## Analysis Steps:

**Data Exploration:** Perform exploratory data analysis to gain insights into the dataset, identify patterns, and understand the distributions and relationships between variables.

**Data Preprocessing:** Clean the data by handling missing values, removing outliers, and encoding categorical variables.

**Feature Engineering**: Create new features or manipulate existing features to minimize feature correlation and improve model performance.

**Feature Selection:** Use techniques like VIF (Variance Inflation Factor) to identify and select important features for the predictive models.

**Model Building:** Train and evaluate various classification models, such as Logistic Regression, Random Forest Classification, and XGBoost Classification, etc.

**Model Evaluation:** Assess the performance of the models using evaluation metrics like Accuracy Score, Recall Score, and F1 Score.

**Hyperparameter Tuning:** Fine-tune the model hyperparameters using techniques like Grid Search or Random Search to improve the model's performance.

**Conclusion:** Summarize the key findings from the analysis, including the most accurate model and the significant features affecting credit card default.

## Results

Here are the key findings from the analysis:

- The Logistic Regression model, after hyperparameter tuning, achieved an Accuracy Score of **68.5%** and a Recall Score of **64.8%**.
- The RandomForest Classification and XGBoost Classification also performed well, achieving accuracies of **80.5%** and **81.4%** respectively.

## How to Access

To view the analysis, follow these steps:

1. **Clone the Repository**: Clone this GitHub repository to your local machine.
2. **Open Jupyter Notebook**: Open the Jupyter Notebook file (`credit_card_default_prediction.ipynb`) included in the repository.
3. **Run the Notebook**: Run the notebook cells to execute the analysis and view the results.
4. **Explore**: Explore the findings and insights presented in the notebook.

## Data Sources

The data used in this analysis is sourced from the Credit Card Default dataset, which contains information on credit card holders including demographic and financial features.

## Feedback

If you have any feedback or suggestions for improving the analysis, feel free to open an issue or submit a pull request. Your input is valuable and helps enhance the quality of this project.
