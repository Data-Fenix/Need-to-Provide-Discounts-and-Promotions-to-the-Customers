# Customer Segmentation Using K Means Clustering
## _To better understand your customers_



## Introduction
Machine Learning techniques are broadly divided into two parts :
1. Supervised Machine Learning
2. Unsupervised Machine Learning

In Supervised Machine Learning, the data is labelled and the algorithm learns from labelled training data. Examples of this method are Classification and Regression.

In Unsupervised Machine Learning, we do not need to supervise the model. Such a method deals with unlabelled data. Unsupervised machine learning helps us find hidden and unknown patterns in data.

Often it easier to get unlabelled data as compared to labelled data, and in such cases, we can use unsupervised machine learning to work on the data. Data, which needs categorization can be categorized with the help of unsupervised machine learning.

Clustering is a type of unsupervised machine learning in which the algorithm processes our data and divided them into “clusters”.

## Discription

Customer Segmentation is the subdivision of a market into discrete customer groups that share similar characteristics. Customer Segmentation can be a powerful means to identify unsatisfied customer needs. Using the above data companies can then outperform the competition by developing uniquely appealing products and services.
The most common ways in which businesses segment their customer base are:

1. `Demographic information`, such as gender, age, familial and marital status, income, education, and occupation.
2. `Geographical information`, which differs depending on the scope of the company. For localized businesses, this info might pertain to specific towns or counties. For larger companies, it might mean a customer’s city, state, or even country of residence.
3. `Psychographics`, such as social class, lifestyle, and personality traits.
4. `Behavioral data`, such as spending and consumption habits, product/service usage, and desired benefits



## Advantages of Customer Segmentation
- Determine appropriate product pricing.
- Develop customized marketing campaigns.
- Design an optimal distribution strategy.
- Choose specific product features for deployment.
- Prioritize new product development efforts.




## The Challenge
You are owing a supermarket mall and through membership cards, you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. You want to understand the customers like who are the target customers so that the sense can be given to marketing team and plan the strategy accordingly.
## K Means Clustering Algorithm
1. Specify number of clusters K.
2. Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.
3. Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.

## Data

This project is a part of the Mall Customer Segmentation Data competition held on Kaggle

## Environment and tools

1. scikit-learn
2. seaborn
3. numpy
4. pandas
5. matplotlib