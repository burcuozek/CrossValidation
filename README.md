# Cross Validation Method and Linear Regression

Cross-validation is a statistical method used to estimate machine learning models' performance (e.g., accuracy). It is used to prevent overfitting in a predictive model, particularly in cases where the number of data points is limited. In cross-validation, you make a fixed number of folds of the data, run the analysis on each fold, and then average the overall error estimate.

One of the most commonly used cross-validation methods is K-fold cross-validation. In this method, the data set is divided into k number of subsets, and the holdout method is repeated k number of times. The steps are as follows: 

- Randomly split your entire dataset into k number of folds (subsets)
- For each fold in your dataset, build your model on k – 1 folds of the dataset. Then, test the model to check the effectiveness for the kth fold
- Repeat this until each of the k-folds has served as the test set
- The average of your k recorded accuracy is called the cross-validation accuracy and will serve as your performance metric for the model.

Linear regression analysis is used to predict the value of a variable based on the value of another variable. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable.

In this project, the cross-validation method and linear regression machine learning model are coded from scratch, creating various functions in Python. For linear regression, standardization and matrix multiplication are coded and used. For cross-validation, splitting the data into training and test dataset is coded and used. 


Author: Burcu Ozek

Reference: 
- https://towardsdatascience.com/what-is-cross-validation-60c01f9d9e75
- https://www.mygreatlearning.com/blog/cross-validation/
- https://www.ibm.com/topics/linear-regression#:~:text=Resources-,What%20is%20linear%20regression%3F,is%20called%20the%20independent%20variable.
