# Sentiment-Analysis-with-Bert-in-Keras
Using BERT model to detect either a review is positive or negative. 

# Information about the dataset
This dataset was created for the Paper 'From Group to Individual Labels using Deep Features', Kotzias et. al,. KDD 2015

It contains sentences labelled with positive or negative sentiment, extracted from reviews of products, movies, and restaurants

## Format:
sentence \t score \n

## Details:

Score is either 1 (for positive) or 0 (for negative)	
The sentences come from three different websites/fields:

imdb.com
amazon.com
yelp.com

For each website, there exist 500 positive and 500 negative sentences. Those were selected randomly for larger datasets of reviews. 
We attempted to select sentences that have a clearly positive or negative connotaton, the goal was for no neutral sentences to be selected.



For the full datasets look:

imdb: Maas et. al., 2011 'Learning word vectors for sentiment analysis'
amazon: McAuley et. al., 2013 'Hidden factors and hidden topics: Understanding rating dimensions with review text'
yelp: Yelp dataset challenge http://www.yelp.com/dataset_challenge

# Instructions
There are 2 jupyter notebooks with all the code. One contains a version without K-fold crossvalidation method, the other it contains it and we can see the differences are quite significant. It can be run locally or on Google Collab.

