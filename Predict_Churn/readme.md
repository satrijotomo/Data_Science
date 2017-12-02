## Predict Customer Churn in Telecom Provider using Machine Learning and R

In this project, we are going to predict the churn customer of telecom sector and find out the key drivers that lead to churn. 
We are going to show how the logistic regression model using R can be used to identify the customer churn in telecome dataset.

Various classifiers are used to find the most accurate classifiers. The classifiers used and tested in this project are:
1. RPART
2. C5.0
3. BST
4. RF (search=random)
5. RF (search=grid)
6. GBM

Most important R libraries used are caret and mlr.

### Outcome
With cross validation, the result shows that C5.0 classifier has the highest accuracy (0.96) and Kappa value (0.81). The Kappa statistic (or value) is a metric that compares an Observed Accuracy with an Expected Accuracy (random chance). It is always less than or equal to 1. A value of 1 implies perfect agreement and values less than 1 imply less than perfect agreement.




