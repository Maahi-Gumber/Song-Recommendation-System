#Song Recommendation System

This project utilizes Python libraries such as pandas, NumPy, Scikit-learn, and SciPy to build a song recommendation system. It suggests songs based on input by analyzing key song characteristics like track ID, artist, popularity, album, and playlist genre.

#Dataset

The dataset comprises 30,000 Spotify songs, sourced from Kaggle. After data cleaning, null values and duplicates were handled, ensuring accurate feature representation.

#Methodology

Key methods used include TF-IDF vectorization for string-based columns (e.g., artist, genre) and standardization for numerical data (e.g., track popularity). These features were combined into a matrix for similarity calculations using cosine similarity. The system then recommends songs based on the most similar entries in the dataset.

#Conclusion

This project demonstrates the potential of machine learning techniques for recommendation systems. Future improvements could include enhanced evaluation methods and optimizing the recommendation algorithm.
