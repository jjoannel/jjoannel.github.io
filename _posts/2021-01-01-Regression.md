---
title: "Overview of Regressions"
date: 2021-01-01
tags:
  - Regression analysis
---

**What problems can regression analysis solve?**

Regression analysis is a type of supervised learning used to predict our response variable. The response variable can be quantitative or qualitative (binary classification or multi-label classification models). 

**Notation for regression models**
Let Y = response, X = X_1,.., X_n denote a list of predictor variables, $\beta$ = 

Popular regression models are: predicting housing prices

**Steps for basic Linear Regression (in R)**
1) Load data into R
3) Summary stats
4) Plot into Dot, Box, Scatterplot and interpret them
5) Run Regression, add regression line to plot
6) Make inferences: Get beta0, beta1, residuals, yhat
7) Interpret slope, intercept
8) Interpret R^2
9) Find residuals, yhat, check for properties
10) Find CI, PI for given X's
11) Plot CI & PI
12) Run visual diagnostics of comment

**Interpretation of Results**

- **R-squared:** The coefficient of determination measures of how well the regression does with respect to the mean.
- **Adj. R-squared:** The coefficient of determination adjusted based on the number of parameters in a model and the number of observations that helped build it.
- **F-statistic:** This is a measure telling you if, from a statistical point of view, all your coefficients, apart from the bias and taken together, are different from zero. In simple words, it tells you if your regression is really better than a simple average.
- **Prob (F-statistic):** This is the probability that you got that F-statistic just by lucky chance due to the observations that you have used (such a probability is actually called the p-value of F-statistic). If it is low enough you can be confident that your regression is really better than a simple mean. Usually in statistics and science a test probability has to be equal or lower than 0.05 (a conventional criterion of statistical significance) for having such a confidence.
- **AIC:** This is the Akaike Information Criterion. AIC is a score that evaluates the model based on the number of observations and the complexity of the model itself. The lesser the AIC score, the better. It is very useful for comparing different models and for statistical variable selection.
- **BIC:** This is the Bayesian Information Criterion. It works as AIC, but it presents a higher penalty for models with more parameters.

Dataset resources:
- https://archive.ics.uci.edu/ml/datasets.php
- https://datasetsearch.research.google.com/
- https://www.kaggle.com/datasets

Books worth reading:
- Regression Analysis with Python, Luca Massaron and Alberto Boschetti. Packt Publishing, 2016.
- Regression Analaysis with R, Giuseppe Ciaburro. Packt Publishing, 2018.
- Applied Linear Regression Models (4th Ed.), Kutner, Nachtsheim and Neter. McGraw Hill, 2003.
- An R Companion to Applied Regression, Author(s): Fox, John, Jr.; Weisberg, Harvey Sanford,Publisher: SAGE Publications, Inc, Edition: 2nd
