# Twitter-Sentiment-Analysis
## Introduction
This project aims to build a sentiment analysis model to classify tweets as positive or negative using the Twitter Sentiment140 dataset. Sentiment analysis is a fundamental NLP task that involves determining the emotional tone behind a piece of text. This project is educational, showcasing data preprocessing, feature extraction, model training, evaluation, and visualization, all while keeping explanations clear for learning purposes.

The Sentiment140 dataset contains 1.6 million tweets labeled as positive or negative, collected from Twitter. Due to hardware constraints, we’ll use a subset of 100,000 tweets (50,000 positive and 50,000 negative) to ensure manageable computation on average hardware.

* 0 - target (sentiment polarity: 0 = negative, 4 = positive)
* 1 - id (tweet id)
* 2 - date (date of the tweet)
* 3 - query (query; often 'NO_QUERY')
* 4 - user (user who tweeted)
* 5 - text (tweet text)

  **This project built a sentiment analysis system using the Sentiment140 dataset, classifying tweets as positive or negative. What we did:**

* Sampled 100,000 tweets for efficiency.
* Preprocessed the data thoroughly with cleaning, tokenization, stop word removal, and lemmatization.
* Extracted features using TF-IDF.
* Trained and compared Logistic Regression, Naive Bayes, SVM and Random Forest Models.
* Evaluated performance with metrics and visualizations.
* Added a practical application function(Testing).
