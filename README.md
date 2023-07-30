# Assessments

This analysis focuses on identifying sentiment analysis based on American moview review website where the sentiment analysis is later trained uisng three different type of supervised ML models. Comparison between the three models are done and the best model that fit this analysis is chose.

The questions that has been discussed in this small project are:
- What are the proportion of sentiments in the dataset?
- What are the top words used for the sentiments?
- Top sentiment distribution of movies, directors, production companies and critics
- The performance evaluation of Logistic Regression
- The performance evaluation of Naive Bayes Theorem
- The performance evaluation of Support Vector Machine
- Which is the best overall ML Model among the three?

## Primary Dataset
Primary dataset that contains general information such as movie_id, movie title, directors, casts, running time and etc. The shape of the dataset is 22 columns and 17712 rows. Required columns is 4. dataset is Rotten Tomatoes Movies And Critics Reviews dataset obtained from Kaggle (File name: rotten_tomatoes_movies.csv).

## Secondary Dataset
Secondary dataset that contains the movie_id, critics names, type of review (Fresh/Rotten), review content and etc. the shape of the dataset is 8 columns and 1048575 rows. Required columns is 4 and can be linked with the primary dataset using movie_id. Dataset is Rotten Tomatoes Movies And Critic Reviews dataset obtained from Kaggle (File name: rotten_tomatoes_critic_reviews.csv).


