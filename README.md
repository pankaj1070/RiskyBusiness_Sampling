# Module_11_Challenge_RiskyBusiness_Sampling

![Credit Risk](Images/credit-risk.jpg)

## Files

[Resampling Starter Notebook](Starter_Code/credit_risk_resampling.ipynb)

[Ensemble Starter Notebook](Starter_Code/credit_risk_ensemble.ipynb)

[Lending Club Loans Data](Resources/LoanStats_2019Q1.csv.zip)

In this assignment I employed different techniques for training and evaluating models with imbalanced classes. I used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the Ensemnle Learning and Resampling.

### Credit risk resampling

Oversampling

Random Oversampling includes selecting random examples from the minority class with replacement and supplementing the training data with multiple copies of this instance, hence it is possible that a single instance may be selected multiple times.

Oversampling techniques used were the following:

Random oversampler

SMOTE (Synthetic Minority Oversampling Technique)

Undersampling

Random Undersampling is the opposite to Random Oversampling. This method seeks to randomly select and remove samples from the majority class, consequently reducing the number of examples in the majority class in the transformed data.

Combination Sampling

This involces combining the two above methods. Using the SMOTE and Edited Nearest Mean (SMOTEENN) techniques.

### Final Questions


1. Which model had the best balanced accuracy score?

The random oversampler, SMOTE, undersampler and combination had the best balanced accuracy score of 0.9948

2. Which model had the best recall score?

All the model had a recall score of 0.99

3. Which model had the best geometric mean score?

All the model had a geometric mean score of 0.99.



### Ensemble Learning

In this section, you will train and compare two different ensemble classifiers to predict loan risk and evaluate each model. You will use the Balanced Random Forest Classifier and the Easy Ensemble Classifier. Refer to the documentation for each of these to read about the models and see examples of the code.

### Final Questions

1. Which model had the best balanced accuracy score?

Balanced Random Forest Classifier had the best balanced accuracy score of 0.99 compared to easy ensemble accuracy score of 0.94

2. Which model had the best recall score?

Balanced Random Forest Classifier had the best recall score of 1 compared to easy ensemble recall score of 0.94

3. Which model had the best geometric mean score?

Easy ensemble had the best geometric mean score of 0.93 compared to Balanced Forest classifier geometric mean score of 0.57