# Predict-english-speaking-region-of-origin-by-analyzing-tweets

Predict the region of origin of an english-speaking tweet author by analyzing tweet content using machine learning classifier

# Project description

In this short project, the objective is to do a content-based classification of english-speaking regions, based on tweets.


# Dataset uset

The dataset used a over 370k tweets from Twitter with authors belonging to 10 different regions. The regions are labelled using the capital city. All tweets are in english and therefore use english language specificities based on the region.

# Classification

A simple SVM classifier is used. The key is to extract linguistic specificities from each region. This is done using a tf-idf vectorizer.

# Results

The classification performance is very good on all regions. Lowest performance achieved with France (Paris) with F1-score of 0.96. This could be explained by the fact that this is not an english-speaking country and therefore features could be weaker and/or by the fact that it is one of two least represented labels in the dataset with Indonesia. Yet F1 score on Indonesia, another non-english speaking country,  reachs 0.99.
Overall accuracy of 98% accross all regions.

![](metrics.jpg)

# Next
- preprocess text to improve performance and robustness
- 
