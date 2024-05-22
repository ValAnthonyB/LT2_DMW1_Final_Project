# Shopping Data Clustering (final project name TBD)

## Introduction
Dataset is from [Kaggle](https://www.kaggle.com/datasets/jacksondivakarr/online-shopping-dataset).

## Dataset
\[PLACEHOLDER\]

## Data Wrangling
* Categorization
* Frequency of purchases
* TF-IDF features

## Exploratory Data Analysis
\[PLACEHOLDER\]

## Clustering
We performed K-Means clustering on two types of features
    a. Purchase frequency per category
    b. TF-IDF vectorization of the category purchases
We found that the TF-IDF features tend to have better separability even without applying PCA. We were able to get eight types of customers with specific purchase behavior.

## Results
\[PLACEHOLDER\]

## EDA wishlist:
1. EDA on the original dataset (which customers are the big spenders? Which customers use coupons?)
2. Which states (in the US) are certain product categories more frequently bought than others?
3. Should we incorporate a new segmentation of the customers based on the average spent? (we can have high value for the big spenders, low value for the low spenders). We want to target high value spenders for marketing campaigns.
4. Which clusters have a high tendency to avail coupons?
5. Which product combinations are commonly bought by each cluster?