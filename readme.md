# Sentiment Analysis on Tweets

As part of Data Mining, Text Mining and Big Data Analytics exam, I performed a sentiment analysis on a  supervised dataset of tweets [Twitter Hate Speech](https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech).

The project is focused on exploring 3 text representation strategies:

* Bag-of-Words (BoW)
* TF-IDF
* Word2Vec (w2v)
* Doc2vec (d2v)

and comparing 3 classifiers:

* Logistic Regression
* Suuport Vector Machine
* XGBoost


## Project WorkFlow
--------------------------------------------
* Understand the Problem Statement
* Tweets Preprocessing and Cleaning
    * Data Inspection
    * Data Cleaning
* Story Generation and Visualization from Tweets
* Extracting Features from Cleaned Tweets
    * Bag-of-Words
    * TF-IDF
    * Word2Vec
    * Doc2vec
* Model Building: Sentiment Analysis
    * Logistic Regression
    * Support Vector Machine
    * XGBoost
* Model Fine-tuning
* Summary

(Please refer to the [NoteBook](https://github.com/jyotiyadav94/Text-Mining-Project/blob/main/Text_Mining_Project%20(1).ipynb) for a more detailed description.)

## How to Run
----------
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pZNwWksXcVohQzonOrMcVzt6dhZsYpCN#scrollTo=zwQaEbGdIm4B)


## Models Training
---------------------------------
I fine tuned XGBoost + Word2Vec with  tree-specific parameters such as max_depth, min_child_weight, subsample, colsample_bytree keeping the learning rate fixed.Tune the learning rate and Finally tune gamma to avoid overfitting.


## Results
--------------------------------------
Here are the models F1-score on Validation set (please refer to section Models Comparison of the notebook for more details).





Here are the models F1-score on test set (please refer to section Models Comparison of the notebook for more details).

## Built With
---------------------------------
Python 3.7

## Author
-------------------------------
[Jyoti Yadav](https://www.linkedin.com/in/jyoti-yadav-64916b160/)


