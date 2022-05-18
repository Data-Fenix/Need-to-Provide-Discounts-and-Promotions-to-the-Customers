# Need to Provide Discounts and Promotions to the Customers?
## K-means Clustering with Mall Customer Segmentation Data
### _To better understand your customers_

<img target="_blank" src="https://github.com/Data-Fenix/Need-to-Provide-Discounts-and-Promotions-to-the-Customers/blob/main/K-means%20Clsutering.png">

## Table of Content

  * [Introduction](#introduction)
  * [Discription](#discription)
  * [Advantages of Customer Segmentation](#advantages-of-customer-segmentation)
  * [Challenges](#challenges)
  * [Data](#data)
  * [Directory Tree](#directory-tree)
  * [Technologies Used](#technologies-used)
  * [To Do](#to-do)
  * [Bug/Feature Requests](#bug-/-feature-requests)
  * [Contributing](#contributing)
  * [License](#license)
  * [Credits](#credits)

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

## Challenges
You are owing a supermarket mall and through membership cards, you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. You want to understand the customers like who are the target customers so that the sense can be given to marketing team and plan the strategy accordingly.

## K Means Clustering Algorithm
1. Specify number of clusters K.
2. Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.
3. Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.

## Data

This project is a part of the Mall Customer Segmentation Data competition held on Kaggle

## Directory Tree

```
├── K-means Clsutering.png
├── K_means_clustring.ipynb
├── Mall_Customers.csv
└── README.md
```

## Technologies Used

1. scikit-learn
2. seaborn
3. numpy
4. pandas
5. matplotlib

[<img target="_blank" src="https://venturebeat.com/wp-content/uploads/2021/02/SageMaker.jpg?fit=1292%2C664&strip=all" width=200>](https://venturebeat.com/wp-content/uploads/2021/02/SageMaker.jpg?fit=1292%2C664&strip=all)[<img target="_blank" src="https://logos-world.net/wp-content/uploads/2021/10/Python-Symbol.png" width = 200>](https://logos-world.net/wp-content/uploads/2021/10/Python-Symbol.png)

## To Do

Need to deploy this model in AWS platform.

Don't worry, we will discss above topics and many more in the future.

## Bug/Feature Requests
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/Data-Fenix/mobile-price-prediction/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/Data-Fenix/mobile-price-prediction/issues/new). Please include sample queries and their corresponding results.

## Contributing

<p><b> ML Enginner </b> : Lahiru Dissanayake </p>
<p><b> ML Enginner </b>: Thamal Adhikari </p>

## License

Copyright 2022 Lahiru Dissanayake and Shashi Withange

## Credits

1) [https://medium.com/@Nivitus./mobile-price-prediction-using-machine-learning-fa9cab6fb242](https://www.analyticsvidhya.com/blog/2021/05/k-means-clustering-with-mall-customer-segmentation-data-full-detailed-code-and-explanation/)
