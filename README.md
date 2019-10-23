# Project 3 - Reddit NLP Classification Models

This project is a part of the curriculum for General Assembly Data Science Immersive.

#### -- Project Status: [Completed]

## Executive Summary

Reddit currently has 330 million active users that regularly visit the site and about 470,000 posts are made daily. Because of this, the world's 13th most visited site. This means there is about 4% of the world is looking at the website every day.  This also means that Reddit has a high chance of reaching out to a large group of people any where in the world, in any time zone.

Right now, we have developed many communication devices, like the advancement of ancient telegraphs to the modern day handphone data messaging, and yet, it is reported that we are getting more and more lonely. This could be due to high migration patterns from rural to urban areas, where young working adults have to leave their families and move to cities for jobs, or decreasing quality of relationships. 

The two subreddits I have chosen, r/relationships and r/justnomil, are known advice/story subreddits that seek advice after explaining their current circumstances. R/relationships aims to help provide advice to posters seeking advice regarding day to day relationships, including familial relationships, friendships and working relationships. On the other hand, R/justnoMIL aims to provide advice and encouragement to posters sharing their current circumstances or seeking validation. 

<results insert> 

It is important that we are able to accurately classify posts from both subreddits as these subreddits may need urgent response from people who may have experienced a similar situation. Urgent responses might be needed especially when posters need immediate psychological care or physical help when placed in dangerous environments of abuse or danger. 

Thus, it is important for posts to be accurately classified in Reddit so that we are able to direct posters to people who can help - or lead them to more qualified help. 

## Problem Statement

### Methods Used
* Data Cleaning Methods
*  Statistical Inference
* Imputation of Missing Data
* Data Scaling
* Basic Modelling techniques
* Regularisation 
* Data Visualization

### Technologies
* Python
* Pandas, jupyter, numpy, scipy
* Matplotlib, Seaborn
* Scikit Learn

## Project Description
- Data was obtained from instructors and cleaned using these sources:
- <https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/submissions>[here]

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- missing data imputation
- statistical modeling
- writeup/reporting

## Getting Started

1. Please clone this repository before using it. 
2. Datasets are kept in .csv files that are contained in [../code/]within this repo.   
3. Data processing/transformation scripts are being kept [../code/]


## Resulting Data Dictionary

### Final Dataframe
|Feature|Type|Description|
|---|---|---|
|'overallqual'|Continuous| Overall material and finish quality|
|'masvnrarea'|Continuous|Masonry veneer area in square feet|
|'poolarea'|Continuous| Pool area in square feet|
|'fireplaces'|Continuous| Number of fireplaces|
|'grlivarea'|Continuous| Above grade (ground) living area square feet|
|'screenporch'|Continuous| Screen porch area in square feet|
|'lotarea'|Continuous| Lot size in square feet|
|'3ssnporch'|Continuous| Three season porch area in square feet|
|'bsmtfullbath'|Continuous| Basement full bathrooms|
|'totalbsmtsf'|Continuous| Total square feet of basement area|
|'garagearea'|Continuous| Size of garage in square feet|
|'yearbuilt'|Continuous| Original construction date|
|'exterqual'|Ordinal| Exterior material quality|
|'kitchenq'|Ordinal| Kitchen quality|
|'bsmtq'|Ordinal| Height of the basement|
|'garagefinish_RFn'|Dummy|  Interior finish of the garage_ Rough Finished|
|'garagefinish_Unf'|Dummy|  Interior finish of the garage_ Unfinished|
|'masvnrtype_BrkFace'|Dummy| Masonry veneer type_Brick Face|
|'masvnrtype_None'|Dummy| Masonry veneer type_ None|
|'masvnrtype_Stone'|Dummy|Masonry veneer type_Stone|
|'heatingq'|Ordinal| Heating quality and condition|
|'paveddrive_P',|Dummy| Partial Paved Drive|
|'paveddrive_Y',|Dummy| Paved Drive|
|'lotshape_IR2',|Dummy| General shape of property_Moderately Irregular|
|'lotshape_IR3',|Dummy|General shape of property_Irregular|
|'lotshape_Reg'|Dummy|General shape of property_regular|
# Project3
