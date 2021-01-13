# Mammogram_classification

## Project's objective

Predict whether a mammogram mass is benign or malignant. 

## Data

The data used for this project comes from the "mammographic masses" public dataset from the UCI repository (source: https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass). 

This data contains 961 instances of masses detected in mammograms, and contains the following attributes:

1. BI-RADS assessment (ordinal) - 1 to 5 
2. Age (integer) - Patient's age in years 
3. Mass shape (nominal)- Mass shape: round=1 oval=2 lobular=3 irregular=4 
4. Mass margin (nominal) - circumscribed=1; micro-lobulated=2; obscured=3; ill-defined=4; spiculated=5
5. Mass density (ordinal) - high=1; iso=2; low=3; fat-containing=4 
6. Severity (binomial) - benign=0 or malignant=1

## Methodology

Data pre-processing:

* Data exploration
* Handling missing data 
* Feature selection 
* Normalization 

Apply several different supervised machine learning techniques and see which one yields the highest.

Models tested:

* Logistic Regression 
* KNN
* Naive Bayes
* Decision Tree
* Random Forest
* SVM
* Neural network

Models are tested using K-fold cross validation (K=10). 
