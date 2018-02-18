# Yelp-Dataset-Sentiment-Analysis-Machine-Learning

- Used NLTK to clean reviews of all users

For each business, 
- Performed statistical analysis of ratings
- Performed sentiment analysis of the ratings for each business (hotel, restaurant)
- Obtained the positive and negative reviews for each business
- Made a word cloud of all positive and negative reviews

Built a user-specific model that identifies a user’s text review vs rating style and predicts the rating for this user
given other user reviews as input

- Used text mining to preprocess the data, applied bag-of-words and TF-IDF to vectorize the cleaned textual data and
used classification techniques to predict the ratings on a scale of 1-5.
- For users with less reviews, performed similarity clustering to identify which user-specific model applies to these users.
