# Bank Marketing Decision Tree Classifier

Welcome to my repository for the decision tree classifier project, which is part of my Data Science Internship at Prodigy InfoTech. In this project, I built a decision tree model to predict whether a customer will subscribe to a product or service based on their demographic and behavioral data using the Bank Marketing dataset from the UCI Machine Learning Repository.

## Overview

The primary objective of this project is to develop a predictive model that assists financial institutions in identifying customers likely to subscribe to a product or service. By analyzing customer data from direct marketing campaigns, the model aims to enhance targeting strategies and improve campaign effectiveness.

## Dataset

The dataset used in this project is the [Bank Marketing](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) dataset. It contains records from a Portuguese banking institution's direct marketing campaigns and includes features such as:

- **Demographic Information:** Age, job, marital status, education, etc.
- **Contact Details:** Communication type, day of the week, call duration, etc.
- **Campaign History:** Number of contacts, previous outcomes, etc.
- **Target Variable:** Indicates whether a customer subscribed to a term deposit (`yes`/`no`).

## Methodology

### Data Preprocessing

- **Data Cleaning:** Checked for and handled missing values and duplicates.
- **Label Encoding:** Applied label encoding to convert categorical variables into numeric values. This step facilitated the correlation analysis and model training.
- **Exploratory Data Analysis (EDA):** A correlation heatmap was generated to explore relationships among numeric features (including label-encoded features).

### Model Development

- **Decision Tree Classifier:**
  - Built a decision tree model to predict customer subscription behavior.
  - Transformed the target variable into a binary format (1 for subscription, 0 for non-subscription).
- **Model Evaluation:**
  - Evaluated the classifier using metrics such as accuracy, precision, recall, and F1-score.
  - Visualized the decision tree to interpret the decision rules based on features like demographic and behavioral data.

## Results

The decision tree model effectively distinguishes between customers who are likely to subscribe and those who are not. Key findings include:

- **Reliable Performance:** The classifier demonstrated satisfactory accuracy on the test set.
- **Interpretability:** The decision tree visualization shows clear splits based on important features, making it easier to understand the model's decision-making process.
- **Actionable Insights:** The model provides valuable insights that can help optimize marketing campaigns and improve customer targeting.

## Conclusion

This project showcases the power of machine learning in predicting customer behavior. By utilizing a decision tree classifier on the Bank Marketing dataset, the model serves as a practical tool for financial institutions to refine their marketing strategies and enhance campaign effectiveness.

Thank you for reviewing my project!
