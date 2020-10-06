# What make a popular or unpopular song?

This project is an analysis on what makes a song popular vs unpopular and what are the common factors that we see in popular songs that we don't see in unpopular songs. For the purpose of this analysis, we look at the relationship between popularity column, and the factors such as danceability, instrumentalness, loudness, liveness, and speecchiness. The entries of the columns are produced by an algorithm created by spotified. 

In addition, we created differents models such as KNN regression, PCA, and predictions. The k-Nearest Neighbors (KNN) regressor whereby the popularity of a song is classified by similarities in values to other songs. To perform a PCA analysis in order to reduce the dimensionality of our data. Using this, we were able to narrow down our data set to a 2-Dimensional set where we plotted popular and unpopular data points to see if there is any relationship between them. To predict the popularity of a song based on the features of each song, so we decided to create models that could do this for us. First, we scaled our data to ensure that our model would not be outweighed by other higher feature values. We specifically scaled our data by dividing each of the rows by the year’s mean/median. 


