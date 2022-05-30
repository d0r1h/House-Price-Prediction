### House Price Prediction

Predicting House Price using Regression Techniques

#

### Notebook


| Notebook | Colab |
| ------ | ------ |
| House Price | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/d0r1h/House-Price-Prediction/blob/main/notebook/House%20Price%20Prediction.ipynb) |
| Hyperparameters Tuning | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/d0r1h/House-Price-Prediction/blob/main/notebook/House%20Price%20Prediction.ipynb) |

### Insights 

1. Target variable is rightly(+ve) skewed. 
2. Minmum SalePrice of a house is 34900 and 755000 maximum 
3. The oldest house is from year 1872 and the most recent built is from 2010
4. Most houses have Garage attached to home
5. GarageArea, GarageCars, GrLivArea, OverallQual, TotalBsmtSF etc. have the correlation of more than .6 with the target variable.
6. There are multiple reasons for a house to be expensive, and some of them are following:
      1. House is in the Northridge Heights Neighborhood
      2. House is located in Residential Low Density zone
      3. House having kitchen quality Excellent
      4. House just constructed and sold

<img src = "assets/targetfeature.png">

### Results

<img src = "assets/ResultScore.png">


### Requirements 

1.scikit-learn
2.xgboost
3.lightgbm
4.optuna
