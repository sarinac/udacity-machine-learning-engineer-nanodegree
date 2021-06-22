# Starbucks Capstone Project

## Overview
This Udacity Capstone is an open-ended project that showcases how to scope a problem, clean and process raw datasets, select and tune models, and ultimately come up with a solution that improves targeted offer campaigns to groups of Starbucks customers. 

[See proposal here](capstone_proposal.pdf).

[See write-up here](capstone_report.pdf).

The final model is a binary classification that determines whether a customer will respond to a particular offer. Gradient boosted trees was the best-performing model with an accuracy score of 72.5%. The strongest features that influenced the prediction was the customer's membership tenure, which is a good reflection of customer loyalty and the importance of customer retention.

## Libraries Used
* `sklearn` for machine learning
* `pandas` for data wrangling
* `sqlite3` for data transformations
* `matplotlib` for visualizations

## Notebooks
* `part_01_data_preparation`
* `part_02_data_exploration_and_feature_creation`
* `part_03_modeling`

## Datasets
#### Raw Sources
* `portfolio.json` - offers
* `profile.json` - customer profiles
* `transcript.json` - 30-day transaction history
#### Intermediate datasets
* `flattened_data.csv` - data flattened with all 3 raw sources
* `data_with_features.csv` - preprocessed data
#### Modeling
* `test.csv` - test data
* `train.csv` - train data

