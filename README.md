# HomeCreditPortfolio

## Business Problem

Many people with limited credit histories struggle to acquire loans from reputable
sources. This is a problem as Home Credit may miss out on potential customers additionally
the customers may fall victim to predatory lending practices elsewhere

## Project Objective

The goal of this analysis is to create predictive machine learning models to distinguish potential customers by their default risk.

## Solution

The solution to our business problem was a collection of models that have different predictive strengths in performance metrics: precision, recall, f1, and auc. The overall best performing model was a Random Forest however the best at capturing high default risk clients was a Naive Bayes model.

## Contributions

My contributions to this project include cleaning and preprocessing data accomplished by running chi2 tests and imputing values for missing data. I also trained and tuned multiple Random Forest models to find a robust predictive model that can meet performance standards.

## Business Value of Solution

If Home Credit can accurately assess which applicants with low credit history are unlikely
to default on loans then they can capture an untapped portion of the market. By expanding the
range of clientele Home Credit loans to, they can increase revenue.

## Difficulties

The most difficult part of this project was preprocessing the dataset. The raw data had a very large number of features and lots of missing data. 

The target variables was very imbalanced among its two classes.

## What I learned
In this project I learned about cost based analysis and altered thresholds within forest nodes to be able to classify a minority class with greater frequency.

I also learned new preprocessing and dimensionality reduction techniques such as chi2 testing for dimensionality reduction and imputation for handling null values.
