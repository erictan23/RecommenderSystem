# RecommenderSystem

This is a CZ4032 Project 1 implementing Recommender System onto datasets for data analysis.

# Members

Tan Jiawei, Eric <br/>
Zon Liew Hur Zhen <br/>
Chan Jun Jie <br/>
Seph Chen Kian Leong <br/>
Samuel Png Yao Wei <br/>

# Requirements
1. Working Editor / Anaconda with Python installed
2. pip install packages inside requirements.txt (Surprise, wordcloud, pandas, scipy, numpy, re, time, nltk)

# Methods

Collaborative Filtering <br/>
Comment-Based Filtering

# How to use the recommender systems?

## Collaborative Filtering
1. **KNN Collaborative** - Optimization will take approximately an hour hence comment it out as it is not required. <br/> get_rec_knn([("movie_title", rating) <br/>
2. **Search Similarity** - new_user1 = [("movie_title", rating), ("move_title", rating)] -> adjust the user's watch list and rating to retrieve recommendations.
3. **Similar Genre Average Ratings** - get_recommendation_netflix(["genre" , "genre"],[]) -> adjust the user's favourite genre for recommendations
## Content Filtering 
 1. Netflix Dataset Recommendation - recommend_netflix(['Movie_Title']) -> Returns you the top 5 netflix recommendation <br/>
 2. IMDB Movie Dataset Recommendation - movie_recommendation(['Movie_Title']) -> Returns you the top 5 movie recommendation <br/>
 

# Data Sets 

For Content Based Filtering: <br/>
IMDB Movies Top 1000 : https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows <br/>
Netflix: https://www.kaggle.com/datasets/shivamb/netflix-shows 

For Collaborative Based Filter: <br/>
netflix_titles.csv <br/>
userDatas.csv (own data in github) <br/>
movies.csv <br/>
ratings.csv : https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa21xZjQyNGE0Qkx0NkFVOUZYM3h6OE4zampBZ3xBQ3Jtc0tsRGM5RHFtWFdXUFdIRTYyQnd0cUJxeldVQWtlaXBYMVQ1cFBRSWhLRk9JUjdsWnBadHJNdWl3QXV3Zkx3QUJwZ1k5ZmFsdTZpODJ5UXEwUjlrdkJFcU5HMmxhQ1ZXY0p6ZHFRQjRlRDJiM2Y1OGE1SQ&q=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1WWQCl9w52M1sXNWd4JSKL7q-HHywk03p%2Fview%3Fusp%3Dsharing&v=3ecNC-So0r4 <br/>

