# Practical MachineLearning At Coursera

## Quiz 1

### Question 1

Which of the following are steps in building a machine learning algorithm?

Answer  | Options
------- | -------
   | Statistical inference
   | Machine learning
   | Training and test sets
 V | Creating features
 
### Question 2
 
Suppose we build a prediction algorithm on a data set and it is 100% accurate on that data set. Why might the algorithm not work well if we collect a new data set?
 
Answer  | Options
------- | -------
 V | Our algorithm may be overfitting the training data, predicting both the signal and the noise.
   | We are not asking a relevant question that can be answered with machine learning.
   | We have too few predictors to get good out of sample accuracy.
   | We may be using a bad algorithm that doesn't predict well on this kind of data.
   
### Question 3

What are typical sizes for the training and test sets?

Answer  | Options
------- | -------
   | 0% training set, 100% test set.
   | 80% training set, 20% test set.
   | 10% test set, 90% training set.
 V | 60% in the training set, 40% in the testing set.

### Question 4

What are some common error rates for predicting binary variables (i.e. variables with two possible values like yes/no, disease/normal, clicked/didn't click)?

Answer  | Options
------- | -------
 V | Sensitivity
   | R^2
   | Root mean squared error
   | Correlation

### Question 5

Suppose that we have created a machine learning algorithm that predicts whether a link will be clicked with 99% sensitivity and 99% specificity. The rate the link is clicked is 1/1000 of visits to a website. If we predict the link will be clicked on a specific visit, what is the probability it will actually be clicked?

Answer  | Options
------- | -------
   | 99%
   | 89.9%
   | 90%
 V | 9%

1/1000 of visits to a website => 100 clicks in 100,000 visits.

TP + FN = 100

Sensitivity = 0.99 = TP/(TP+FN) = 99/(99+1)

TN + FP = 100,000-100 = 99,900

Specificity = 0.99 = TN/(TN+FP) = 98,901/(98901+999)

TP/(TP+FP) = 99/(99+999) = 9%