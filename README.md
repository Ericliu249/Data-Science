# Predicted churn rate reduction for Telephone Services using Marketing Analytics

- Contact: yliu249@stevens.edu, eric.liu.249@gmail.com

## Introduction
Customer churn, also known as customer attrition, is the loss of clients or customers. Telephone service companies have tremendous demand for customer churn analysis because the cost of retaining an existing customer is far less than acquiring a new one. In other words, recovered long-term customers can be worth much more to a company than newly recruited clients. One common way that companies used to retain customers who are going to churn is marketing to the target customers and giving them benefits. However, companies’ budgets for retaining the potential churned customers are limited. Only a portion of customers can be selected as marketing targets, which raises some questions. How many and which customers should companies select? How much discount should they offer to customers? These questions can be solved by marketing analytics.  

In this project, we attempted to use marketing analytics to find the optimal solution for a telecom company branch to make more profit by decreasing its churn rate. We took three steps to achieve the optimal solution. First, we visualized the data by Tableau and Python to find the relationships between variables. Second, we trained six classification models, logistic regression, KNN, Naïve Bayes, linear discriminant regression, random forest classification, and AdaBoost Classifier, to predict the customer churn. At last, we built an optimization model using Solver to find the optimal solutions for marketing to reduce churn. 

From the result, we found that both logistic regression and Naïve Bayes had the best accuracy of the classification model and the telecom company branch can make 1,919,904 more profit by the optimization model.
