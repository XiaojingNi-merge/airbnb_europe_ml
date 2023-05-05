
# ANLY 512 Final Project Group 15

## Airbnb Price Prediction in European Cites

* Xiaojing Ni xn19@georgetown.edu
* Xin Xiang xx123@georgetown.edu
* Yanfeng Zhang yz1045@georgetown.edu

## Executive summary

Our study aims to analyze how different features are correlated with room listing prices and to develop accurate pricing predictions based on specific features. To achieve this goal, we employed several machine learning models, including linear regression with regularization (i.e., lasso, ridge), polynomial regression with lasso regularization, random forest, and XGBoost, on the Airbnb European dataset. Among the models, XGBoost achieved the best performance, outperforming both the non-linear regression and linear models in terms of testing errors. In addition, our tree-based models indicated that environmental features, such as proximity to the city center or attraction index, play a more critical role in predicting listing prices than property features, such as room type. Our study contributes to the existing literature by providing insights into the Airbnb market in Europe where there is a higher degree of geographical variation. Our findings may help homeowners adjust pricing strategies, and also assist travelers in booking properties that fit their budget and preferences.


## Repository structure

```.
├── README.md
├── code/
├── data/
```

## Description of files


* The `code/` directory contains all codes file during EDA process with following sub-directories:
    * `code_for_eda/`: Codes for initial EDA including `EDA.ipynb`,`visualization_xn19.ipynb`.
    * `code_for_model/`: Codes for different model including `linear.ipynb`, `non-linear.html`, `ridge-lasso.ipynb`, `bagging-boosting.ipynb`, `model_summary.ipynb`.


* The `data/` directory contains all data files with following sub-directories:
    * `Aemf1.csv`: Raw data directly from original data scoures
    * `train.csv`: In data split 70% of the data is trian data
    * `test.csv`: In data split 15% of the data is test data
    * `dev.csv`: In data split 15% of the data is dev data

    
## Airbnb Cleaned Europe Dataset

Source: https://www.kaggle.com/datasets/dipeshkhemani/airbnb-cleaned-europe-dataset

### About Dataset
This is a merged dataset of 9 famous cities in Europe.

Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, Paris, Rome and Vienna.

The original Dataset was really messy and lacked describing appropriate information.

Perform analysis and tell a story you'd like to tell with this dataset.

Column names are self-explanatory.

