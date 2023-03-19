# twitter-sentiment-analysis

# Sentiment-Analysis-on-Rings-of-Power-from-Amazon-Prime-Movies

This project involves the collection of tweets related to Rings of Power from Amazon Prime Movies, cleaning and preprocessing the data, performing sentiment analysis, and evaluating the performance of different machine learning algorithms.

#Data-Collection

I collected tweets using the Twitter API by searching for tweets containing the keywords "Rings of Power" from the Amazon Prime Movies account. I collected 10000 tweets between the dates of 2022-07-30 and 2022-10-01.

# Data-Cleaning-and-Preprocessing

The collected tweets were cleaned and preprocessed using the data_processing() function, which involves the following steps:

Lowercasing the text
Removing user mentions (@username)
Removing hashtags (#)
Removing retweets (RT)
Removing URLs
Removing special characters and punctuations
Removing stopwords
Stemming the words

# Sentiment-Analysis

The sentiment analysis was performed using three different machine learning algorithms: Logistic Regression, LinearSVC, and GridSearchCV. The performance of these algorithms was evaluated using metrics such as accuracy, precision, recall, and F1 score.

# Conclusion

In this project, I performed sentiment analysis on tweets related to Rings of Power from Amazon Prime Movies. We collected the data using Twitter scraping, cleaned and preprocessed the data, and used machine learning algorithms to classify the tweets as positive or negative. The performance of these algorithms was evaluated using various metrics, and the best performing algorithm was selected.
