# Anime_recommendation_system

## Files:


- Anime ratings csv/all ratings csv:
    - Anime ratings csv was just the anime ratings we webscraped
    - All ratings csv is cleaned with sentiment score and vector score
    
- Webscraping my animelist notebook:
    - web scraping script to gather all the data from myanimelist

- anime ratings eda notebook:
    - analyzing the data we have prior to starting any models to get an idea of challenges to come
 
- Cleaning and modeling the data 1 and 2:
    - seperate notebooks for my partner and i to work on where we did the nlp data, vectorizing and modeling of all our data
    
- anime rec system pdf:
    - pdf of the final presentation 
    
- Visuals folder:
    - includes all the visuals used in the presentation (ie: histogram of user scores, user review sentiment and vector scores, average rating for anime with a ton of reviews, most active users)
![](Visuals/Screen%20Shot%202020-06-16%20at%208.04.04%20PM.png)


## Task: 
Create an Anime Recommendation system based on user ratings and user review text data.

## Purpose: 
Generate recommendations for people who like anime and want to find something to watch.

## Process:

### Webscraping:
Gather reviews and ratings for over 1000 anime from myanimelist.net.

### Data Cleaning:
Clean the NLP data using regex and tokenizer

### Create word vectors and word sentiments:
Use Spacy and TextBlob to convert the user reviews into a single vector score or sentiment score

### Recommendation System:
Use all the different rating scores to make different models and gridsearch to tune the models.
