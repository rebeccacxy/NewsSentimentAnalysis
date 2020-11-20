# Sentiment analysis on Financial News

I used 3 algorithms - BERT using Simple Transformers, Neural Network and Decision Trees. 

The BERT model performed the best, and obtained a consistent accuracy of ~85%. 

For data preprocessing, stopwords were removed, thereafter the stemmed and lemmatized text were derived with NLTK. Lemmatized text performed better than stemmed text in terms of accuracy, after being fed into the neural network. 

Overall, I ranked 3rd in the NUS Fintech internal kaggle competition. 

https://www.kaggle.com/c/nus-fintech-news-headline-sentiment-analysis/leaderboard
