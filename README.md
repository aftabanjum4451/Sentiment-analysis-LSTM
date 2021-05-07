# Movie-Review-Sentiment-analysis
This is a mini project, in which I designed the model for sentiment analysis, and the dataset I used is: Movie-Review. The data contain raw text and its sentiments. 
## Dataset
(https://www.cs.cornell.edu/people/pabo/movie-review-data/)

## Libraries Needed
- transformers
- contractions
- torch
- sklearn
- numpy
- pandas
- nltk
- re
- glob
- os
- inspect

## Embedding Used 
-	Word2Vec
-	Custom Word Embedding 
-	Pre-trained Glove embedding (300 dimension)

## Description 
In this work, I have done pre-processing including: stemming, stop words and punctuation removal. After that, I have performed some data analysis to analyse the data, then I trained three **LSMT models** with three different embedding, and at the end checked the performance of each model.

Also, I have noted all the comments and heading in the code for your understanding
