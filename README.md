# Movie Recommender
movie recommender that learns latent factors for each user and item and uses them to make rating predictions.

**Data**:
[MovieLens dataset](http://grouplens.org/datasets/movielens/), which includes
* movie information (`data/movies.dat`)
* user information (`data/users.dat`)
* users' ratings

**Model Tool**:
* Dato GraphLab Factorization Recommender

**Evaluation**:
* Predict rating for each user-movie combination &rarr; select the top 5% of movies recommended and compare against actual ratings in the test data &rarr; score based on the average of those ratings.
