# Movie_Rating_Statistics
A Python Solution using Apache Spark to determine Movie Rating Statistics based on data including user ratings, movie genres, and rating frequency.

## Purpose
This python notebook is run on the Palmetto Supercomputer and reads in explicity-named files. The python code, coupled with Apache Spark, uses high performance computing principles and design patterns in order to determine statistics about data collected from user's movie ratings. 

We use this data to efficiently determine the following statistics:
*   For each genre:
  *  Median of all user ratings
  *  Mean of all user ratings
  *  Standard Deviation of all user ratings
*   The user who rates most frequency
*   The most frequent user's favorite genre


## Source Files
* MovieRatings.html
  *  HTML file showing the Python notebook script and its output.
* MovieRatings.ipynb
  *  Python Notebook which can be opened in an Apache Spark context.
* movies.csv
  *  CSV file that contains information about all rated movies including:
    *  movieId - Unique identifier or foreign key for each movie
    *  title - Movie Title (may include ',')
    *  genres - All '|' separated list of each of the genres that the movie belongs to
* ratings.csv
  *  CSV file that contains information about ratings submitted by users including:
    *  userId - Unique identifier or foreign key for each user
    *  movieId - Unique identifier for each rating's respective movie
    *  rating - Float value representing the user's satisfaction with the movie
    *  timestamp - Time that the rating was submitted by the user
