# Ensembles - Recap

## Key Takeaways

The key takeaways from this section include:
* Multiple independent estimates are consistently more accurate than any single estimate, so ensemble techniques are a powerful way for improving the quality of your models
* Sometimes you'll use model stacking or meta-ensembles where you use a combination of different types of models for your ensemble
* It's also common to have multiple similar models in an ensemble - e.g. a bunch of decision trees
* Bagging (Bootstrap AGGregation) is a technique that leverages Bootstrap Resampling and Aggregation
* Bootstrap resampling uses multiple smaller samples from the test dataset to create independent estimates, and aggregate these estimates to make predictions
* A random forest is an ensemble method for decision trees using Bagging and the Subspace Sampling method to create variance among the trees
* With a random forest, for each tree, we sample two-thirds of the training data and the remaining third is used to calculate the out-of-bag error
* In addition, the Subspace Sampling method is used to further increase variability by randomly selecting the subset of features to use as predictors for training any given tree
* `GridsearchCV` is an exhaustive search technique for finding optimal combinations of hyperparameters 
* Boosting leverages an ensemble of weak learners (weak models) to create a strong combined model
* Boosting (when compared to random forests) is an iterative rather than independent process, using each iteration to strengthen the weaknesses of the previous iterations
* Two of the most common algorithms for Boosting are Adaboost (Adaptive Boosting) and Gradient Boosted Trees
* Adaboost creates new classifiers by continually influencing the distribution of the data sampled to train each successive tree
* Gradient Boosting is a more advanced boosting algorithm that makes use of Gradient Descent
* XGBoost (eXtreme Gradient Boosting) is one of the top gradient boosting algorithms currently in use
* `XGBoost` is a stand-alone library that implements popular gradient boosting algorithms in the fastest, most performant way possible
