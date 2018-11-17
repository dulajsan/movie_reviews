# movie_reviews
Sentiment analysis of movie reviews data-set

# Preprocessing steps

accents removal
html escape sequence removal
html tags removal using beautifulsoup4
expand the contractions
remove special characters
remove stop words

# features tested

Bag-of-words
tf-idf
bigram

# classification

SVM
Logistic Regression

# Results

Accuracies

| First Header   | bow           | tf-idf    | bigram    |
| -------------  | ------------- | --------- | --------- |
| SVM            | 84.68%        | 81.35%    | 79.84%    |
| Logistic Reg.  | 86.37%        | 82.49%    | 80.02%    |



