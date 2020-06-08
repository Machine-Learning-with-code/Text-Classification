# Text-Classification

This is a repository for trying different types of text classifcation algorithms.

Data used: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data (saved in 'data' folder)

There are various steps involved in Text Classification:
1. Cleaning and Preprocessing
2. Feature Extraction    
    2.1 Bag of Words    
    2.2 TF-IDF    
    2.3 Word2Vec   
    2.4 GloVe (Pre-Trained)   
    2.5 GloVe (Trained)   
    2.6 FastText   
    2.7 Contextualized Word Representations
3. Dimensionality Reduction
4. Classification Models   
    4.1 Naive Bayes   
    4.2 Support Vector Machine   
    4.3 Basic LSTM   


# Results:
| Models | Naive-Bayes |
| --- | ----------- |
| Score | |
| Time Taken | |



1. Bag of words models
2. Naive Bayes
3. Support Vector Machine
4. Deep Learning - RNN
5. Deep Learning - CNN
    https://machinelearningmastery.com/best-practices-document-classification-deep-learning/


This one is amazing:
https://medium.com/text-classification-algorithms/text-classification-algorithms-a-survey-a215b7ab7e2d
https://machinelearningmastery.com/develop-word-embedding-model-predicting-movie-review-sentiment/
https://towardsdatascience.com/machine-learning-nlp-text-classification-using-scikit-learn-python-and-nltk-c52b92a7c73a
https://github.com/brightmart/text_classification
Post on Medium: https://towardsdatascience.com/text-classification-in-python-dd95d264c802
- Code on GitHub: https://github.com/miguelfzafra/Latest-News-Classifier



https://www.toptal.com/machine-learning/nlp-tutorial-text-classification

https://www.analyticsvidhya.com/blog/2018/04/a-comprehensive-guide-to-understand-and-implement-text-classification-in-python/
https://towardsdatascience.com/machine-learning-nlp-text-classification-using-scikit-learn-python-and-nltk-c52b92a7c73a

FastText: https://medium.com/@ageitgey/text-classification-is-your-new-secret-weapon-7ca4fad15788

Various Models for Classification: https://github.com/brightmart/text_classification
Bag of words, rnn model: https://machinelearnings.co/tensorflow-text-classification-615198df9231

https://machinelearningmastery.com/deep-learning-bag-of-words-model-sentiment-analysis/
https://machinelearningmastery.com/develop-word-embedding-model-predicting-movie-review-sentiment/

Feature Engineering:
2.1 Count Vectors as features
2.2 TF-IDF Vectors as features

    Word level
    N-Gram level
    Character level
2.3 Word Embeddings as features
2.4 Text / NLP based features
2.5 Topic Models as features


Theory:
https://nlp.stanford.edu/IR-book/html/htmledition/text-classification-and-naive-bayes-1.html
Coursera Course:
https://www.coursera.org/lecture/python-text-mining/identifying-features-from-text-8nUhf



Data used: https://www.kaggle.com/bittlingmayer/amazonreviews
Kernels: https://www.kaggle.com/bittlingmayer/amazonreviews/kernels



In this repo, we'll do a quick intro of Word Embeddings then carry out Text classification using word embeddings.  

# Word-Embeddings

Word Embedding is a learned representation for text where words that have the same meaning have a similar representation. Individual words are represented as real-valued vectors in a predefined vector space. This is advantageous over the representaton by one hot encoding/Bag of words which has a lot of 0s in the vectors and miss out on capturing the semantic relations of words (as all words as considered to be independant).  
Quick intro Reference - https://towardsdatascience.com/what-the-heck-is-word-embedding-b30f67f01c81

## Types of Word Embedding
1. Frequency based Embedding
    - Count Vectors
    - TF-IDF
    - Co-Occurrence Matrix
2. Prediction based Embedding
    - CBOW
    - Skip-Gram
  
To read in detail about above and more - https://www.analyticsvidhya.com/blog/2017/06/word-embeddings-count-word2veec/


# Let's start with the Classification

## Some Important Preprocessing Steps to begin with
Many of these can be done with the help of the [nltk package](https://github.com/nltk/nltk). They can be referenced in the [insert code folder link]
1. Removing Stop words
2. Tokenizing
3. Stemming
4. Lemmatization
5. Part of Speech Tagging
6. Named Entity Recognition
7. And more...
  
Reference - https://medium.com/@datamonsters/text-preprocessing-in-python-steps-tools-and-examples-bf025f872908


Toxic comment classification with word embeddings:

Fasttext - https://www.kaggle.com/doha2012/toxic-comment-word-embeddings-and-cnn  
Glove - https://www.kaggle.com/ajithvajrala/word-embeddings-with-tfidf-ensemble
