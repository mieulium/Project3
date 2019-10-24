# Project 3 - Reddit NLP Classification Models

This project is a part of the curriculum for General Assembly Data Science Immersive.

#### -- Project Status: [Completed]

## Executive Summary

Reddit currently has 330 million active users that regularly visit the site and about 470,000 posts are made daily. Because of this, the world's 13th most visited site. This means there is about 4% of the world is looking at the website every day.  This also means that Reddit has a high chance of reaching out to a large group of people any where in the world, in any time zone.

Right now, we have developed many communication devices, like the advancement of ancient telegraphs to the modern day handphone data messaging, and yet, it is reported that we are getting more and more lonely. This could be due to high migration patterns from rural to urban areas, where young working adults have to leave their families and move to cities for jobs, or decreasing quality of relationships. 

The two subreddits I have chosen, r/relationship_advice and r/justnomil, are known advice/story subreddits that seek advice after explaining their current circumstances. R/relationship_advice aims to help provide advice to posters seeking advice regarding day to day relationships, including familial relationships, friendships and working relationships. On the other hand, R/justnoMIL aims to provide advice and encouragement to posters sharing their current circumstances or seeking validation. 

It is shown that there is merit in using a Naive Bayes model with a TF-IDF vectorizer to predicting our posts due to the decreased incorrectly classified results. This is evidence that it is possible to provide redditors a helping hand to decide where to seek advice from. 

It is important that we are able to accurately classify posts from both subreddits as these subreddits may need urgent response from people who may have experienced a similar situation. Urgent responses might be needed especially when posters need immediate psychological care or physical help when placed in dangerous environments of abuse or danger. 

Thus, it is important for posts to be accurately classified in Reddit so that we are able to direct posters to people who can help - or lead them to more qualified help. 

## Problem Statement:
We normally consult the internet first for all our problems whether it be physical, mental or social, thus there is a need to 'triage' our problems so that immediate attention can be given. We propose a way to classify the posts more effectively so that the appropriate help can be given. 

### Methods Used
* NLP Data Cleaning Methods (e.g. Lemmatizing, Regex)
* Pipeline
* GridSearch
* Logistic Regression
* Naive Bayes 
* Data Visualization

### Technologies
* Python
* Pandas, jupyter, numpy, scipy
* Matplotlib, Seaborn
* Scikit Learn

## Project Description
- Data was obtained from these sources:
- <https://www.reddit.com/r/relationship_advice>[here] and <https://www.reddit.com/r/JUSTNOMIL>[here]

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- modeling
- writeup/reporting

## Getting Started

1. Please clone this repository before using it. 
2. Datasets are kept in .csv files that are contained in [./code/]within this repo.   
3. Data processing/transformation scripts are being kept [./code/]


## Results

Though all models have acceptable scores, with both models scoring consistently above 0.99, the Naive Bayes Model performed better than the logistic regression models in both score overall and in detecting less false negatives. 

In addition, the overall accuracy of the Logistic Regression model seem to be less accurate. It might not be favourable to use Logistric Regression to classify posts as the nature of r/JUSTNOMIL can often require specific advice from other likeminded individuals, and the severity of r/JUSTNOMIL posts might require immediate attention. The Logistic Regression model showed that there was a higher proportion of false negatives - which means that there are more r/JUSTNOMIL posts being incorrectly classified as r/relationship_advice.

Thus, the Naive Bayes model has more merit as classifier as it is able to firstly classifies less wrong posts, and secondly, it has a higher AUC score in general

Furthermore, there is a slight advantage of using TF-IDF word vectorizer as the models using it contains less false positives. 

## Possible Future Steps of Action

If it is possible to explore further, the following courses of action might be suitable:
- introducing regularisation to the logistic regression model
- try decision trees instead    
- develop tool further to decide on danger level of poster. 
