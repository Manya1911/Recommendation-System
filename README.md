# Movie Recommendation-System
## Introduction
This project is a Movie Recommendation System built using Python. It leverages data from the TMDB 5000 dataset to recommend movies based on a combination of features including genres, overview, keywords, cast, and crew. The recommendation system uses the Bag of Words technique and cosine similarity to find and suggest similar movies.

## Dataset
The project uses the following datasets:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

## Python Libraries Used
Pandas: For data manipulation and analysis (reading datasets, handling missing values, merging data).
NumPy: For numerical operations (support for multi-dimensional arrays and matrices).
Scikit-learn: For machine learning algorithms (creating the Bag of Words model, computing cosine similarity).
NLTK (Natural Language Toolkit): For natural language processing (using PorterStemmer to reduce words to their root form).
