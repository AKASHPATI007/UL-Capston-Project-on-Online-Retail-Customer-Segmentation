# UL-Capston-Project-on-Online-Retail-Customer-Segmentation

# This project is aimed at predicting the case of customers' default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the KS chart to evaluate which customers will default on their credit card payments.

This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.

X2: Gender (1 = male; 2 = female).

X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).

X4: Marital status (1 = married; 2 = single; 3 = others).

X5: Age (year).

X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows:

X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.

X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.

X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005


# Business Objectives---

Objective of our project is to predict which customer might default in upcoming months. Before going any further let's have a quick look on definition of what actually meant by Credit Card Default.

The research aims at developing a mechanism to predict the credit card default beforehand and to identify the potential customer base that can be offered various credit instruments so as to invite minimum default.

# Operations performed--

Removing null and duplicates

Feature Engineering

Handling Outliers

EDA

Model Training

Model Tuning

Model Evaluations

# Key Findings From Eda---

The number of people who will default their payment is much less than number of people of people who will pay on time

The Number of females are much more than males in our dataset (6,224) and we can also say that females tend to pay their default on time compared to their male counterparts

Married people are more likely to pay their default payments compared to singles and others

We can also say that Singles do not pay their default payment marginally as compared to married counterparts

From pairplot 1 Bill amount for each month is highly correlated with each other hence we will try to feature engineer bill amount to Dues column to reduce multicollinearity

From pairplot 2 we can see that pay amount tends to clutter at one place hence we can try to feature engineer pay amount columns to one payment column to declutter our data

From history of past payment analysis it is clear that most people who pay duly are not likely to default their payment

Here, we can say from age 21 to 39 limit balance is increasing however from 39 to 60 it started to decline.

# Conclusion-----------

In our dataset, We used many algorithm like Logistic Regression,Support vector classsifier,decision tree classifier,XGBoost Classifier,Random Forest Classifier.

Random Forest was the best performing algorithm as shown below

Random Forest Classifier has the best value of accuracy score of 84%

Random Forest Classifier has the best value of precision score of 84%

Random Forest Classifier has the best value of recall score of 83%

Random Forest Classifier has the best value of f1 score of 84%

Random Forest Classifier has the best value of Roc_auc score of 84%

This proves Random Forest Classifier algorithm has perfectly fitted all the dataset

