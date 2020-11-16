# MarketingClassification

## Contents

[**1. Requirements**](#Requirements)

[**2. Background**](#background)

[**3. Motivation**](#motivation)

[**4. Results**](#results)

## <a name="Requirements">Requirements</a>


    Python 2.7
    Numpy >= 1.14.2
    Matplotlib >= 2.2.0
    Pandas >= 0.22.0
    Scikit-Learn >= 0.19.1

## <a name="background">Background</a>

This repository contains models built on [Bank Marketing Data set](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing) available from UCI ML repository. The classification goal is to predict wheather a customer will accept the 'CD' (Certificate of Deposit) offer based on various customer related and previous campaign related data.

[This notebook](https://nbviewer.jupyter.org/github/des137/MarketingClassification/blob/master/eda.ipynb) quickly performs the basic data exploration to ascertain the intrgrity of the data.

## <a name="DATA SET INFORMATION">DATA SET INFORMATION</a>
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

## <a name="MODELS">MODELS</a>
Among the machine learning models that were tested on this particular dataset, I have predicted y with different models such as SVM, Random Forest and Logistic Regression. The ac
Output:

We have to predict if the client will subscribe a term deposit or not (variable y).

## <a name="results">Results</a>

Business decision usually provides a better context for deciding how many False Positives vs. False Negatives are acceptable.The accuracy of 89 percent is reached and implemented using Logistic Regression. 


