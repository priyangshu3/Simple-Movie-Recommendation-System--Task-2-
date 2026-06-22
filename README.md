# Movie Recommendation System

## Objective

Build a simple movie recommendation system using Machine Learning and Natural Language Processing (NLP) techniques.

## Dataset

TMDb 5000 Movies Dataset from Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Files Used:

* tmdb_5000_movies.csv
* tmdb_5000_credits.csv

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

## Project Workflow

### 1. Data Collection

Loaded the TMDb movie dataset containing movie titles, genres, and overviews.

### 2. Data Preprocessing

* Selected relevant columns.
* Removed missing values.
* Prepared movie descriptions for analysis.

### 3. Feature Engineering

* Applied TF-IDF (Term Frequency-Inverse Document Frequency) vectorization on movie overviews.
* Converted text data into numerical vectors.

### 4. Similarity Calculation

* Used Cosine Similarity to measure similarity between movies.
* Generated a similarity matrix.

### 5. Recommendation System

* Implemented a Content-Based Filtering approach.
* Recommended the top 5 similar movies based on user input.

## Sample Output

Input:
Avatar

Recommended Movies:

* Aliens
* Titan A.E.
* Moonraker
* Battle: Los Angeles
* Star Trek

## Key Concepts Used

* Content-Based Recommendation
* TF-IDF Vectorization
* Cosine Similarity
* Natural Language Processing (NLP)

## Conclusion

A movie recommendation system was successfully developed using content-based filtering techniques. The system analyzes movie descriptions and recommends similar movies based on textual similarity.

## Author

Priyangshu Bagchi
Data Science Intern
