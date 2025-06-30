
![Alt text](https://github.com/Alokrao91/Bank-Churn-Prediction/blob/main/image.png?raw=true)


# Bank-Churn-Prediction
Unlocking Customer Retention Insights.

Utilizing machine learning to predict customer churn based on behavioral, demographic, and financial data.

Empowering banks to take proactive steps to improve customer loyalty and reduce attrition.

# Conclusion
Customer churn is a major challenge for banks, as it affects both revenue and the long-term value of customers. This project aimed to build a machine learning model that can predict whether a customer is likely to leave the bank (churn), using information such as demographics, financial data, and account activity.

Our predictive model classifies customers as either likely to stay (Exited = 0) or leave (Exited = 1). The most important factors influencing churn were identified as Age, Estimated Salary, Credit Score, and Account Balance.

Among the models tested, Random Forest and XGBoost performed the best, each achieving an accuracy of 86%.

Since the dataset was imbalanced (more non-churners than churners), we applied resampling techniques to the training data to improve the model's ability to detect customers likely to churn. However, further improvement can be achieved by experimenting with more advanced sampling methods.

To prepare the data for modeling, we converted categorical variables like Geography and Gender into numerical format (int64), which is required by machine learning algorithms.

We evaluated each model using a range of performance metrics, including:

1)F1 Score

2)Recall

3)AUC (Area Under the Curve)

4)Confusion Matrix

5)Accuracy Score

6)Classification Report

Additionally, hyperparameter tuning was applied to optimize each model for better predictions.
