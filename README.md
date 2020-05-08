# Mod4Project
Movie Recommendation System

# Goal
The goal of this project is to recomended movies. I have created a model to predict what movie a user would like,
what the user would rate movies, and a model that gives you similar movies based on the genre. 

#Target
The target of the model is to give a user movies based on their ratings and preferences. I have also implemented a way that gives
a user his top 5 mosst recomended animation movies. 

#Predictors
The only data used for this project was movie lens small data set found here: https://grouplens.org/datasets/movielens/latest
This model only uses the genre of a given movie along with the users rated movies. 

# Data Cleaning
Data did not need to be cleaned heavily. Genres had to be split for preprocessing and the lenght of the ratings was above one hundred thousand.
Used twenty-five percent of the due to the lack of processing power. 

#EDA:

Rating distribution of animation movies

https://lh4.googleusercontent.com/LXWukFBr9aqvOWKCXCwgyqJiQducVY7FubAU0MOJ-Kld6Z1FesQBqZe5Dkb5v24ZugtxO5EBKY1eBejVofLjBj396uQfIMdCuVZ7TvY

Word cloud of animation movies

https://lh6.googleusercontent.com/1u0Iu6XgeEGz1HqXieO84OU6TNk9OciW5JE8kDvkbasVu-i_LwxFj3RD6TheHnIqkfvuoy_UpshihXlU2jgL8V-nHBD2VMG_HpnqOmoX

Word cloud of animation genres

https://lh6.googleusercontent.com/GhR4HmeZfUO6LCtypPbCcRem50y3I-uXqYF_W9Sn79auCpShPF2k4Kd4yCl1HaK80E6SLX05hgJZGXuK7LJFEx_P4NbEfsYxRlk3aNlW

# Models:
Content Based Recommendation:
- Model Predicts similarity between movies based on movie genre
SVD Model
- Reduced Dimensionality Model

# Results:
Top 5 movies recommended to user ID 20:
- Toy Story
- Galaxy Quest
- Monty Python and the Holy Grail
- Mrs. Doubtfire
- Finding Nemo

Top 5 Animimation movies recommended to User ID 20:
- Inside Out
- Laputa: Castle in the Sky
- My Neighbor Totoro
- Corpses Bride
- Howl’s Moving Castle

Ratings that User ID 20 would give to:
- No Game No Life: Zero: 3.5
- Toy Story: 4.4
