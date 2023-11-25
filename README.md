# Movie Recommendation System

This Movie Recommendation System suggests movies similar to a user-inputted movie based on content features such as genres, keywords, cast, crew, and overview using natural language processing techniques and cosine similarity.

## Files

- **recommendation_system.py**: Python script containing the recommendation system implementation.
- **tmdb_5000_credits.csv**: Dataset containing movie credits information.
- **tmdb_5000_movies.csv**: Dataset containing movie details.

## Data Preprocessing

- Merged movie credits and details datasets.
- Extracted and cleaned features (genres, keywords, cast, crew, and overview).
- Applied natural language processing to create movie tags.

## Model

- Utilized CountVectorizer to convert text data into numerical vectors.
- Calculated cosine similarity between movie tags to suggest similar movies.

## Acknowledgments

- the TMDB 5000 Movie Dataset available at [TMDb](https://www.themoviedb.org/).
