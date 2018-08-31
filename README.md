# My solution to Santander Value Prediction Challenge 2018

I with my BIG team (23 people) ranked 108th (TOP 3%) in the [Santander Value Prediction Challenge](https://www.kaggle.com/c/santander-value-prediction-challenge). It was a fun adventure due to the size of the team, but I made a significant contribution to our result and I want to share some of our code.

## In this repository you can find:
* BoostARoota and lgb.ipynb - notebook in which I used a BoostARoota library to select useful features and learning my best LGBM model, which was used in the final ensemble
* cross validation 20x5.ipynb - code of our cross validation scheme with 100 folds
* five folds CV (only for fast tests).ipynb - notebook with simple kfold validation for quick testing of ideas
* prepare data.ipynb - notebook with my data processing code (statistical features, space reduction features(PCA, TruncatedSVD, FastICA, FactorAnalysis, SparseRandomProjection, GaussianRandomProjection) and other)
