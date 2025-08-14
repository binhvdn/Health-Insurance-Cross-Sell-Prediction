# Health-Insurance-Cross-Sell-Prediction
# Description:
This project aims to predict whether an existing health insurance customer is likely to purchase vehicle insurance. The dataset contains customer demographics, policy details, and vehicle-related information. The goal is to identify potential cross-sell opportunities, enabling targeted marketing efforts.

# The workflow involves:
- Data Import & Preprocessing – Loading the dataset, handling missing values, and preparing features for modeling.
- Exploratory Data Analysis (EDA) – Understanding data distributions, relationships between variables, and key influencing factors for cross-sell likelihood.
- Model Development – Building and evaluating classification models, including Logistic Regression, with a focus on handling class imbalance.
- Evaluation Metric Priority – Since the business objective is to capture as many potential buyers as possible, recall for the positive class (1) is prioritized over other metrics.
Final Model Choice – Logistic Regression was selected for its high recall score (93%) on the positive class, ensuring minimal loss of prospective customers.
# Key Outcome:
A prediction model that enables the insurance company to proactively identify customers most likely to purchase vehicle insurance, improving marketing efficiency and conversion rates.
