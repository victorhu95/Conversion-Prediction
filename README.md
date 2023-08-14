# Conversion_Prediction

## Goal:## Understand user behavior and predict conversion rate based on user data.

Challenge: The dataset contains several features, such as the user's country, age, and the number of pages visited during their session. The primary challenge is to extract meaningful insights from this data and build a predictive model that can accurately predict whether a user will convert.

Key Steps:

Data Exploration: Started by loading and exploring the dataset to understand its structure and characteristics.
Data Visualization: Visualized the distribution of different features and their impact on conversion rates. Identified key patterns, such as the variance of conversion rates across countries and the relation between age and conversion.
Data Preprocessing: Handled outliers (unrealistic age values) and transformed categorical variables using one-hot encoding.
Modeling:
Logistic Regression: Served as a baseline model and achieved an AUC score of approximately 0.985.
Random Forest: An ensemble model that can capture more complex relationships. Achieved an AUC score of around 0.949.
Gradient Boosting Machine (GBM): A boosting algorithm known for high performance. Achieved an AUC of roughly 0.984.
Evaluation: Used the ROC curve to visualize and compare the performance of the models. Both Logistic Regression and GBM performed exceptionally well.

![image](https://github.com/victorhu95/Conversion_Prediction/assets/44851564/506ea48d-e102-4466-830d-136de6a6cedb)


Key Insights:

Younger users have a higher propensity to convert.
The number of pages a user visits is directly correlated with their likelihood to convert, highlighting the importance of user engagement.
There are significant variances in conversion rates across countries, with China having a notably lower rate.
Recommendations: Based on the insights, it's recommended to focus marketing efforts on younger demographics and invest in improving website engagement. Further, strategies should be revised for markets like China where conversion rates are lower.

Future Steps: Further fine-tuning of the models, exploration of more complex algorithms, and feature engineering can enhance prediction accuracy. Additionally, exploring why certain markets like China have low conversion rates can provide deeper insights.
