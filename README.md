# Sentiment prediction of Yelp reviews 
### This notebook showcases the importance of natural language representation in sentiment predicitive models

+ We use yelp data set for classifying reviews into positive or negative sentiments
+ We use random forest as our classifier
+ We use two language representaion for reviews:
    + Bag of words
    + Word-2-vec

Intutively, word-2-vec model takes into account local structure of words in sentences and exploits this locality to trasform words into a numeric space where, sentimentally speaking, closely related words are close to each other. On the other hand, bag of words ignores this inherenet locality.

The quantitative results show that on the same dataset word-2-vec model acheives better classification accuracy **boosting the AUC from 0.9 to 0.93**.
