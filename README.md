# Movies-Recommendation-System
## Overview
This project implements a movie recommendation system using content-based filtering techniques. The system suggests movies to users based on the similarity between movie descriptions (overview) and genres. By analyzing user preferences and movie features, the recommendation system aims to provide personalized movie suggestions.

## Dataset
The dataset used for this project is sourced from [https://www.kaggle.com/datasets/ahsanaseer/top-rated-tmdb-movies-10k]. It consists of information about the top-rated TMDB (The Movie Database) movies, including movie titles, genres, overviews, and other relevant details.

## Dependencies
Python 3.x
NumPy
pandas
scikit-learn

## Usage
1. Data Preprocessing:
Load the dataset and perform data cleaning (handle missing values, outliers, etc.).
Extract relevant features such as movie titles, genres, and overviews.

2. Feature Engineering:
Combine textual features (overviews and genres) to create a consolidated feature vector for each movie.

3. Vectorization:
Use CountVectorizer to convert textual features into numerical representations.

4. Similarity Calculation:
Compute cosine similarity between movie feature vectors to measure their similarity.

5. Recommendation:
Implement the recommendation function to suggest top similar movies based on user input.

Example:  recommand("Schindler's List")

## Results
The recommendation system successfully suggests top similar movies based on the input movie.
The system can be further optimized and extended by incorporating additional features and advanced recommendation algorithms.

## Future Work
Explore hybrid recommendation approaches combining content-based and collaborative filtering techniques.
Deploy the recommendation system as a web application to provide real-time movie suggestions to users.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or create a pull request.
