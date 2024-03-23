# Logistic Regression for Placement Prediction

This repository contains a Python implementation of logistic regression applied to predict placement outcomes based on CGPA (Cumulative Grade Point Average) and IQ scores. The dataset used here consists of three columns: 'cgpa', 'iq', and 'placement', where 'cgpa' and 'iq' are predictor variables, and 'placement' is the response variable indicating whether a student got placed or not.

## Dataset
The dataset used for this analysis is as follows:
- `cgpa`: Cumulative Grade Point Average of the student.
- `iq`: IQ score of the student.
- `placement`: Binary variable indicating whether the student got placed (1) or not (0).

## Logistic Regression
Logistic regression is a statistical method used for binary classification tasks. It models the probability that a given instance belongs to a particular class. In our case, logistic regression can be used to model the probability of a student getting placed based on their CGPA and IQ scores.

### Mathematical Formulation
The logistic regression model can be represented by the following equation:

![Logistic Regression Equation](https://wikimedia.org/api/rest_v1/media/math/render/svg/4fa8df8db7fc384a880f1b0dfb83d3b772fde3f1)

### Implementation
The implementation of logistic regression for placement prediction can be found in the provided Python script. It includes data preprocessing, model training, and evaluation.

## Conclusion
Logistic regression is a powerful tool for binary classification tasks like placement prediction. By analyzing features such as CGPA and IQ scores, we can make informed decisions about the likelihood of a student getting placed.

For more information on logistic regression and its applications, refer to the references provided in the script.

## References
- [Logistic Regression - Wikipedia](https://en.wikipedia.org/wiki/Logistic_regression)
- [Scikit-learn Documentation: Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
