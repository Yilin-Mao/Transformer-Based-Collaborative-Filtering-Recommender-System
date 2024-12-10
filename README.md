# Transformer-Based-Collaborative-Filtering-Recommender-System

The code is based on this article https://medium.com/hepsiburada-data-science/personalized-recommendations-with-transformers-11c13cff2be with some adjust to adapt to the latest movielens dataset and illustrate the performance intuitively with figure.

The dataset used in the article is movielens-1m which is released in 2003. We use a smaller (100k ratings) yet latest dataset (last updated in 2018). Since the data features are different (e.g. latest dataset does not include user information file) and also the dataset size is smaller, we adjust the model structure (e.g. simplify the model dimension, use regularizer and Adam optimizer, adjust the training set ratio and so on) to fit the dataset and solve the problem like overfitting. Finally, we plot the performance chart based on NDCG score to illustrate the result more clearly.

Codes for 1m and latest dataset are both offered. Further work like comparing performance with other recommendation model may be done.
