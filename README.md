# Movie Recommendation Systems

This repository contains implementations of movie recommendation systems using different techniques. Below are the details of each implemented system:

## 1. Genre, Cast, and Crew-based Recommendation System

### Implementation:
- **Libraries Used**: pandas, scikit-learn (CountVectorizer, cosine_similarity)
- **Data Used**: "tmdb_5000_movies.csv" and "tmdb_5000_credits.csv"
- **Functionality**: This system recommends movies based on similarities in genres, cast, and crew.
- **Preprocessing**: 
  - Merged the movie and credits datasets.
  - Cleaned and preprocessed data by transforming genres, cast, and crew into a suitable format.
- **Algorithm**: Used CountVectorizer to create feature vectors and cosine similarity for recommendation.
- **Usage**: Call `get_recommendations(title)` function with a movie title to get recommendations.

## 2. Genre and Cast-based Recommendation System

### Implementation:
- **Libraries Used**: pandas, scikit-learn (CountVectorizer, cosine_similarity)
- **Data Used**: "tmdb_5000_movies.csv" and "tmdb_5000_credits.csv"
- **Functionality**: This system recommends movies based on similarities in genres and cast.
- **Preprocessing**: 
  - Merged the movie and credits datasets.
  - Cleaned and preprocessed data by transforming genres and cast into a suitable format.
- **Algorithm**: Used CountVectorizer to create feature vectors and cosine similarity for recommendation.
- **Usage**: Call `get_recommendations(title)` function with a movie title to get recommendations.

## 3. Overview-based Recommendation System

### Implementation:
- **Libraries Used**: pandas, scikit-learn (TfidfVectorizer, linear_kernel)
- **Data Used**: "tmdb_5000_movies.csv"
- **Functionality**: This system recommends movies based on similarities in movie overviews.
- **Preprocessing**: 
  - Cleaned and preprocessed data by handling missing values and transforming overviews into a suitable format.
- **Algorithm**: Used TF-IDF Vectorizer to create feature vectors and linear kernel for cosine similarity.
- **Usage**: Call `get_recommendations(title)` function with a movie title to get recommendations.

## Usage:
- Each recommendation system can be tested by running the provided code snippet with a movie title of your choice.

