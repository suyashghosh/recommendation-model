# recommendation-model
Collaborative Filtering for Book Recommendations

This model demonstrates a recommendation model based on the technique of [Collaborative Filtering](https://developers.google.com/machine-learning/recommendation/collaborative/basics)
Dataset(https://www.kaggle.com/ruchi798/bookcrossing-dataset)


Collaborative filtering uses similarities between users and items simultaneously to provide recommendations. This allows for serendipitous recommendations; that is, collaborative filtering models can recommend an item to user A based on the interests of a similar user B.


The steps in the model are as follows:
1. Map user ID to a user vector via an embedding matrix
2. Map isbn to a book vector via an embedding matrix
3. Compute the dot product(Matrix Factorization) between the user vector and book vector, to obtain a predicted rating
4. Train the embeddings via gradient descent using all known user-book pairs.

