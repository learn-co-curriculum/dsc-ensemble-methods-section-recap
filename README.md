
# Section Recap

## Introduction

This short lesson summarizes key takeaways from section 30

## Objectives
You will be able to:
* Understand and explain what was covered in this section
* Understand and explain why this section will help you become a data scientist

## Key Takeaways

The key takeaways from this section include:
* Parameters are the "settings" for a given model - for a linear model in the form y = mx + c, the parameters are m and c
* Maximum Likelihood Estimation returns the values for the parameters of a model that maximize the chance that the observations were created by that model
* When calculating maximum likelihood we often use a log likelihood to simplify calculations (allowing us to decompose products into simpler sums)
* It's important to consider algorithmic bias when building models as biased observations will tend to generate a biased model (if banks are less likely to provide loans to African Americans, a model trained on such data is likely to perpetuate that bias)
* Gradient descent is a method for traversing a cost curve to find a local minima or maxima (or saddle point)
* A sigmoid function can be used to map a linear regression model to a range from 0 to 1, allowing for a logistic regression which can be used as a binary classifier
* A regularization parameter can be used to apply a cost to overfitting, reducing the likelihood of overfitting your model

