# Movie-recommender-system

MovieLens 100k Dataset:
MovieLens 100K movie ratings. Stable benchmark dataset. 100,000 ratings from 1000 users on 1700 movies.

Dataset can be downloaded from the following link:
https://grouplens.org/datasets/movielens/100k/

MovieLens 20M Dataset:
MovieLens 20M movie ratings. Stable benchmark dataset. 20 million ratings and 465,000 tag applications applied to 27,000 movies by 138,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.

Dataset can be downloaded from the following link:
https://grouplens.org/datasets/movielens/20m/

A recommender system is a system that predicts ratings or preferences, a user might give to an item. Often, these are sorted and presented as “top-N recommendations”. Also known as recommender engines, recommendation systems, and recommendation platforms.

Recommender systems are used for rating things (Amazon, Flipkart, etc.), rating content (Youtube, Netflix, New York Times, etc.), rating music (Pandora), rating people (Dating sites), and rating search results (Google).

One of the most interesting event that boosted the research on Recommender Systems is the Netflix Competition (2006-09) where it was asked to improve the RMSE of the Netflix existing recommender system by 0.1 and won by BELLKOR. 

My project is a movie recommendation system using several techniques including content-based recommendation, collaborative based system (User-based and item-based), Matrix Factorization techniques (SVD), Deep Learning (RBM), and Hybrid methods on MovieLens 10K dataset to provide top-N recommendations. Also, I applied the ALS method in Apache spark to recommend movies from MovieLens 20M Dataset which resembles the real-world data.

Metrics used for the project include Accuracy measures like MAE, RMSE, etc., Hit Rate, Average Reciprocal Hit Rate, Coverage, Diversity, Novelty, and Churn.
