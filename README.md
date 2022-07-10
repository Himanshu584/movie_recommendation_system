# movie_recommendation_system

movie recommendation model made on TMDB 5000 movie dataset :- https://www.kaggle.com/tmdb/tmdb-movie-metadata

recommendations made on basis of `cosine similarity`

process of building model :- 
   1. preprocessed the data 
   2.  applied stemming on 'tags' column
   3.  vectorised the tags column
   4.  calculated the similarity between movies using Cosine_similarity 
   5.  developed recommendation function which returns 5 similar movies when a movie is passed on to it as argument
