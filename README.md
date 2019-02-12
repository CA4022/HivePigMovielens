# HIVE and PIG on Movielens

For this Lab, we will use the MovieLens Small Dataset to examine the functions
of HIVE and PIG. Both of these applications can either run on top of a working
HDFS / Mapreduce cluster, or they can run in local mode.

# Tasks

1. Obtain the MovieLens Latest Small dataset
<http://grouplens.org/datasets/movielens/>

1. Load the MovieLens Dataset files with pig and then query them with Hive
    1. With pig, you will need to clean and orgalize the data, including, among others:
        * split multiple genres
        * fix delimiters
        * separate year from title
        * decide which files to merge or not into single tables
        * etc... based on what queries/exploration/analysis you want to run
1. With HIVE you need to explore the data you have structured by running some queries as per example below (in order of difficulty):
    * What is the Title of the Top-rated Action / Comedy movie?
    * What is the User with the highest average rating?
    * What is the most popular rating and how are ratings distributed across the dataset?
    * How are ratings distributed by genre?
    * ... anything you want to query about tags?

Read the <http://files.grouplens.org/datasets/movielens/ml-latest-small-README.html> for the details of how the files are organised.

Useful Links on Hive and MovieLens:
* https://liamgavinmurray.com/2014/04/13/evaluating-film-user-behaviour-with-hive/
* https://ragrawal.wordpress.com/2013/09/14/detecting-gender-bias-per-movie-genre-using-hive/


