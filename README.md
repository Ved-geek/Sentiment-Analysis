# Sentiment-Analysis

## Introduction

Sentiment analysis or opinion mining is the computational study of people’s opinions, sentiments, attitudes, and emotions expressed in written language. It is one of the most active research areas in natural language processing and text mining in recent years. Its popularity is mainly due to two reasons. First, it has a wide range of applications because opinions are central to almost all human activities and are key influencers of our behaviors. Whenever we need to make a decision, we want to hear others’ opinions. Second, it presents many challenging research problems, which had never been attempted before the year 2000.

## Problem Statement:

Designing a NLP model which can predict whether the reviews of restaurant are positive or negative.

We will use here some restaurant reviews data. Each observation consists in one customer review for one restaurant. Each customer review is composed of a textual feedback of the customer’s experience at the restaurant and an overall rating.
For each textual review, we want to predict if it corresponds to a good review (the customer is happy) or to a bad one (the customer is not satisfied).

## Implementation

1. Start with reading the datasets by using the different packages in Python. 

2. Perform the process of data cleaning by using the removing null values. 

3.  TEXTBLOB library will be used to get the polarity of the reviews and with the help of that, the sentiment of reviews will be found out of training data. 

4. Bag of words will be created. 

5. Machine Learning model will be applied to train the model. 

6. Then we have split the data into Training and Testing Data for our model. 

7. For Training we have used 70% of our dataset and for Testing we have used remaining 50% of our dataset along with the BOW technique and Countvectorizer function. 

8. We have used Random Forest Algorithm for our model and after testing we have evaluated the result by obtaining the accuracy.

## Architecture

![image](https://user-images.githubusercontent.com/57028947/122230232-132def00-ced7-11eb-900c-55d34c3518b3.png)
