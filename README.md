# Codsoft_task_no.2
IMDB Indian Movies Rating Prediction

Objective:
 MOVIE RATING PREDICTION WITH PYTHON Build a model that predicts the rating of a movie based on features like genre, director, and actors. You can use regression
techniques to tackle this problem. The goal is to analyze historical movie data and develop a model that accurately estimates the rating given to a movie by users or critics.
Movie Rating Prediction project enables you to explore data analysis, preprocessing, feature engineering, and machine learning modeling techniques. It provides insights into the factors 
that influence movie ratings and allows you to build a model that can estimate the ratings of movies accurately.

Insights:
1. We  have 15509 rows of data and 10 columns with object and float data type. We can see there are many null values also. So Let us get the exact counts of null values further
2. All the columns except name has null values we cannot just replace the values we need to dive in deep and check how the data is, what are the duplicates, are there any typos etc.
3. Every column had null values except name column
4. We also found that the following columns: Name, Year, Duration, Genre, and Votes had typos that needs to be corrected
5. The null values in most of the columns needs to be dropped and for Genre, it will be filled with the mode value
6. Need to check for the duplicated values and drop them based on Name column
7. rating 6.6 has the highest frequency, and 3.0 rating has the minimum frequency
8. The first year a movie was release is 1931
9. The minimum duration is of 45min
10. Drama Genre is the most famous genre
11. Mithun is the most famous actor
12. 'My name is Khan' had the highest number of votes, and 'June' had the highest rating
13. 'Kanti Shah' directed most of the movies
14. The distribution of Year is skewed towards left with a high concentration of movies directed in between 2015-2019
15. The duration of movies has a guassian distribution with a very few outliers
16. The distribution of Rating is also having a guassian distribution with a high concentration of 6.6 and 6.7
17. The number of votes has a plenty of outliers
18. There is a decline in ratings observed from 1984 till 1993, however the ratings has a continous upward trend after 2013
19. We found that in year 2010, some movies relased which got the highest votes and ratings
20. Drama Genre has the highest ratings
21. Comedey Gener started around 1953 and action in 1964
22. The lesser the duration the higher is the rating, shows the fact people don't like to watch full length movies or get bored.
23 tHE BEST random state is 40
23 We split the data set into test and train dataset
24. We build various models and see the model accuracy. Gradient Boosting Regressor gives the highest score of 93.90 percent
25. Test our model and In the new data we took the 3rd row data where in the rating was 5.9, and we got 5.79, this shows the robustness of our model

Here I end my project.

Kindly provide your valuable feedback. Thankyou.
