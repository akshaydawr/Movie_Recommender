# Movie-Recommendation-System

Build a content-based movie recommender system that reads content from an overview of movies and generates TF-IDF matrix and finds cosine similarity of each movie with other movies and Displays Top similar movies.

# Objectives

1. Represent Movies: Convert this data into a format that can be used for similarity calculations. For example, you might use TF-IDF vectors for movie descriptions or embeddings for movie features.

2. Calculate Similarity: Use a method to compute how similar each movie is to others. One common approach is cosine similarity, which measures how similar the content of two movies is by comparing their vectors.

3. Create Recommendations: For a given movie, find other movies that are most similar based on the calculated similarity scores

# Core Concepts

1. Data Preparation: We create a DataFrame with movie titles and descriptions.

2. TF-IDF Vectorization: Convert movie descriptions into numerical vectors using TF-IDF.

3. Cosine Similarity: Compute similarity scores between all pairs of movies based on their TF-IDF vectors.

4. Recommendation Function: Find the index of the input movie, Get similarity scores for all other movies. Return the titles of these top similar movies.


# Technologies Used

1. python, pandas, numpy

2. sklearn, vectorizer

3. cosine distance similarity.