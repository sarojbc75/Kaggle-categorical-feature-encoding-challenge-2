# Kaggle-categorical-feature-encoding-challenge-2
Categorical Feature Encoding Challange-2

Because this is such a common task and important skill to master, we've put together a dataset that contains only categorical features, and includes:

binary features
low- and high-cardinality nominal features
low- and high-cardinality ordinal features
(potentially) cyclical features
This follow-up competition offers an even more challenging dataset so that you can continue to build your skills with the common machine learning task of encoding categorical variables. This challenge adds the additional complexity of feature interactions, as well as missing data.

This Playground competition will give us the opportunity to try different encoding schemes for different algorithms to compare how they perform

In this competition, we will be predicting the probability [0, 1] of a binary target column.
The data contains binary features (bin_*), nominal features (nom_*), ordinal features (ord_*) as well as (potentially cyclical) day (of the week) and month features. The string ordinal features ord_{3-5} are lexically ordered according to string.ascii_letters.

Since the purpose of this competition is to explore various encoding strategies. Unlike the first Categorical Feature Encoding Challenge, the data for this challenge has missing values and feature interactions.
