# Movie Recommendation System Using Spark
# **Group Members:**

1. Sanya Zaveri AU1920064
2. Kavya Patel AU1940144
3. Kairavi Shah AU1940177


<div class="h2"><center>Introduction</center></div>


Recommendation systems having been much present right now, there are so many approaches to make and improve they.<br>
We can find they in online shops, music streaming and video streaming services.<br>
In this Kernel, We made an EDA on [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset) and got the data used for movie ratings to build a Recommendation System with Alternating Least Square (ALS), with it, it will be possible make a user based system or a item based system.<br>
<br>
For this job, We will work with Pandas Dataframes, visualizations with Altair, printable text with BeautifulText and PySpark for ALS.<br>

In all the data info displayed, we can see that only ratings have a large memory usage, and I will use this dataset to make the recommendation system based on user ratings, the dataset have the relevant data like userId, movieId and ratings.<br>
It's important to say that the ratings dataset doesn't have any missing value, therefore, will not needed any treatment like data imputation or drop NA rows.<br>
The other datasets will be used for Exploratory Data Analysis.

<div class="h3">Let's start with the following approaches</div><br>
* Rating Frequency.
* Analysis of most rated movies.
* World cloud with most common words.

Let's start plotting an Histogram to see the rating distribution.
