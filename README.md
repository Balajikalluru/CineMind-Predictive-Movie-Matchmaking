# CineMind-Predictive-Movie-Matchmaking

This project is a content-based movie recommender system built using Python, pandas, NLTK, and scikit-learn. The goal of this system is to recommend movies based on their similarity to a given movie. The system processes movie data to create a feature set that captures the key attributes of each movie, and then calculates the similarity between movies to generate recommendations.

### Features
##### Data Preparation:<br/>
Loaded and processed a dataset containing movie attributes such as budget, genres, keywords, cast, crew, and more.
Extracted relevant information and formatted it for analysis.<br/>
##### Tag Creation:<br/>
Combined multiple textual features into a single tags column for simplified text processing.<br/>
##### Text Processing:<br/>
Used NLTK's PorterStemmer for stemming to reduce words to their root forms.
Applied scikit-learn's CountVectorizer to convert text data into feature vectors, limiting to the 5000 most common words and removing English stop words.<br/>
##### Similarity Calculation:<br/>
Computed cosine similarity between movie vectors to measure the similarity between different movies.<br/>
##### Recommendation Function:<br/>
Implemented a function recommend that takes a movie title as input, finds its corresponding index, calculates similarity scores with other movies, and returns the top 5 most similar movies.

This movie recommender system leverages text processing and machine learning techniques to provide personalized movie recommendations based on content similarity. It is a simple yet effective implementation suitable for learning and extending further.
