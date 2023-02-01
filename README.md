# 2022 U of MN Travelers Modeling Competition Classifier Model: Auto Quote Conversion

### If you want to see all the details of the projcet, please check the [project report](STAT8051_Project_Report_JooyongLee.pdf).

<br/>

## Summary

To significantly contribute to a business strategy, this project will identify quoted policies that Peace of Mind Insurance Company will convert (a.k.a. issue) and reveal factors to determine which features of customers or policies impact conversion rate. Three significant steps to proceed with the project are Exploratory Data Analysis (EDA), feature engineering, and fitting models.

<br/>

## Datasets
Peace of Mind Insurance Company offers three different datasets:
Policies.csv, Drivers.csv, and Vehicles.csv. Every dataset includes policy id as an attribute as a unique customer identifier. Policies.csv consists of a train and test set, and a conversion indicator is missing for policies in the test set, and a conversion model this
project will suggest will predict those.

<br/>

## Feature Engineering
**Data imputation method**: Multiple Imputations with Multivariate Imputation by Chained Equations (MICE) algorithm.

**Converting Zip code**: Due to large number of classes for feature Zip, it is converted to longitude and lattitude.

<br/>

## Machine Learning Models
- Logistic Regression
- Random Forest
- XGBoost



