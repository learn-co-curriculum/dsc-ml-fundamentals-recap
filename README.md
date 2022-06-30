# Machine Learning Fundamentals - Recap

## Introduction

In this section you used a familiar model, linear regression, to learn about machine learning fundamentals.

## Key Takeaways

* ***Inference*** and ***prediction*** are two different use cases for statistical modeling
  * Linear regression can be used for both kinds of modeling
  * While inference is most interested in understanding relationships in the data, prediction is most interested in ***generalization***, i.e. making good predictions on unseen data
* ***Model validation*** techniques allow you to measure how well your model generalizes
  * The two most popular validation techniques are ***train-test split*** (which randomly shuffles the data into a training set and a test set) and ***cross-validation*** (which splits the data into folds and uses one fold at a time as the test set)
* Predictive modeling involves balancing between ***bias*** and ***variance***
  * Bias is associated with ***underfitting*** and less-complex models
    * An example of a less-complex model would be linear regression
    * A high-bias model will perform poorly on both the training and the test data
  * Variance is associated with ***overfitting*** and more-complex models
    * An example of a more-complex model would be polynomial regression
    * A high-variance model will perform well on the training data and poorly on the test data
* ***Regularization*** is a technique to reduce overfitting
  * Two popular penalized coefficient regularization techniques are ***ridge*** regression and ***lasso*** regression
  * Lasso regression penalizes coefficients to 0, which means that it can be used for ***feature selection*** in addition to other feature selection techniques such as recursive feature elimination
