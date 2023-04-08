# Credit_card_Default_pred_Capstone_3

**Project Name** - Credit card Deafault Prediction.

**Project Type** - Classification

**Contribution** - Individual

**Project Summary -** This project is aimed at predicting the case of customers' default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of

This project aims to predict credit card default using a classification model. The dataset used is from a bank in Taiwan, which contains various demographic and financial attributes of their clients.

A variety of classification algorithms, such as logistic regression, decision tree, and random forest, are implemented to build predictive models. The models are evaluated using performance metrics such as accuracy, precision, recall, and F1 score.


**Problem Statement**

The problem statement is that banks face significant risks associated with credit card defaults, which can result in substantial financial losses. Predicting credit card defaulters is therefore essential for banks to manage their credit risk, allocate resources effectively, and offer competitive rates to their customers.

The current challenge is that traditional credit risk assessment methods may not be sufficient to accurately predict credit card defaults. To address this problem, there is a need to develop advanced predictive analytics models that can leverage large amounts of data to identify patterns and trends that traditional methods may overlook.

The objective of this project is to develop a predictive model that can accurately forecast credit card defaults, allowing banks to make informed decisions on how much credit to extend to individuals and adjust interest rates based on the predicted risk. This model will also enable banks to proactively identify high-risk accounts and take preventative measures to reduce the risk of defaults.

By addressing this problem, the proposed solution can help banks optimize their credit risk management processes, reduce bad debt expenses, and promote financial stability for their customers.

**Results Of ML Models**

**KNN Classification:**

* Higher precision and recall for class 0 (non-default) compared to class 1 (default)
* Lower accuracy (0.71) compared to the other two models
* Performs relatively well at identifying non-default cases, but struggles with identifying default cases.

**Logistic Regression:**

* Lower precision and higher recall for class 0 compared to class 1
* Lowest accuracy (0.67) among the three models
* Performs relatively well at identifying default cases, but struggles with identifying non-default cases

**Random Forest with Randomized Search CV:**

* Highest accuracy (0.80) among the three models
* Highest precision for class 0 and relatively high recall for both classes
* Performs relatively well at identifying non-default cases, but struggles with identifying default cases compared to class 0

**There are several potential areas for future scope:**

Feature engineering: There may be other features that could be extracted or created from the existing data, such as the difference between the bill amount and payment amount for each month, or the percentage of credit used by each customer.

Hyperparameter tuning: It may be possible to further improve the performance of the models by fine-tuning their hyperparameters. For example, the number of trees in the Random Forest model or the regularization parameter in the Logistic Regression model could be adjusted.

Ensemble methods: Ensemble methods, such as combining the predictions of multiple models or using boosting or bagging techniques, could be explored to further improve the accuracy and robustness of the predictions.

Class imbalance: The dataset may have class imbalance, which means that there are significantly more examples of one class (e.g., non-defaulters) than the other class (e.g., defaulters). Techniques such as oversampling or undersampling could be used to balance the classes and improve the performance of the models.

Interpretability: While the performance of the models is important, it is also important to understand how they are making their predictions. Techniques such as feature importance ranking, partial dependence plots, or SHAP values could be used to gain insights into the factors that are driving the predictions of the models.

Real-time deployment: Once a model has been developed and trained, it could be deployed in a real-time environment to make predictions on new data. Techniques such as containerization or serverless computing could be used to deploy the models in a scalable and cost-effective way.

**Conclusion**

In conclusion, the project aimed to develop a machine learning model for predicting credit card defaulters based on a given dataset. Three different models were evaluated: KNN Classification, Logistic Regression, and Random Forest with Randomized Search CV. Based on the results, the Random Forest model performed the best in terms of accuracy, precision, and recall.

The most important features for predicting credit card defaulters were found to be gender, education, marital status, maximum credit given, age, payment status, bill amount, and payment amount. However, the importance of each feature may vary depending on the specific dataset and problem being addressed.

Future scope for the project includes exploring feature engineering, hyperparameter tuning, ensemble methods, class imbalance, interpretability, and real-time deployment. These areas of research could further improve the performance and applicability of the machine learning models for predicting credit card defaulters.

**Overall, the project provides insights into the factors that are important for predicting credit card defaulters and demonstrates the potential of machine learning for solving real-world problems in the finance industry.**
