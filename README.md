# Bank-Customer-Churn-Prediction

Objective: The goal of this project was to predict which customers are likely to leave (churn) a banking service using machine learning techniques, enabling the bank to take proactive steps to retain at-risk customers and reduce revenue loss.

Dataset:
A publicly available dataset from Kaggle was used, which includes customer demographics, account details, and churn status.

Tools & Techniques:
Python: For data preprocessing, exploratory data analysis (EDA), and model building.
Pandas, Seaborn, Matplotlib: Used for data manipulation and visualizations.
Scikit-Learn: For machine learning model development.

Steps Involved:
Exploratory Data Analysis (EDA):

Investigated customer churn distribution across various features such as tenure, balance, country, gender, and age.
Key insights: Customers with shorter tenure, zero balance, and from specific countries like France were more prone to churn. There was no significant impact of credit score or salary on churn.
Feature Engineering:

One-hot encoding was applied to categorical features like country and gender.
Key features used in the model: balance, tenure, products_number, and encoded categorical variables.
Model Development:

Logistic Regression was initially chosen as a baseline model for binary classification.
Random Forest was also implemented to improve performance through an ensemble approach.

Model Evaluation:

The Logistic Regression model achieved an accuracy of 81%, with a precision of 0.55 for predicting churners, but a recall of only 0.20, indicating that the model struggled to capture all churners.
Despite good accuracy, improving recall was critical to better identify customers at risk of churn.

Business Impact:
The model helped the bank identify high-risk customers for proactive retention strategies, which could reduce potential revenue loss.

Revenue Forecast: Based on the model’s predictions, the bank forecasted potential churn and took action to prevent losses from customers at risk.
Retention Campaigns: By targeting customers predicted to churn, the bank could save annually if it retained 30% of the at-risk customers.

Outcomes:
Prediction: The model predicted that 144 customers were at high risk of churning, with an opportunity to retain 30% of them through targeted retention efforts.
Optimization: Recommendations included refining the model’s recall by tuning the decision threshold or using advanced models like Random Forest and XGBoost to improve predictive performance.

Key Takeaways:
This project showcases my ability to:

Apply machine learning techniques for predicting customer churn and delivering actionable insights to improve business retention strategies.
Conduct thorough data analysis to understand patterns, correlations, and drivers of churn.
Build, evaluate, and optimize predictive models to inform business decisions, ultimately driving revenue growth and customer retention.
