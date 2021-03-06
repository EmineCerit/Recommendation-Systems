# Movie Recommender Item Based Filtering Application

## Table of contents
* [Introduction](#Introduction)
* [Context](#Context)
* [Business Problem](#Business_Problem)
* [Attribute Information](#Attribute_Information)

![image](https://user-images.githubusercontent.com/83332641/161719301-9223e24c-794b-47ea-92db-ef359cfa30b1.png)

<a id="Introduction"></a>
## Introduction  
Item based collaborative filtering is a memory-based algorithm for recommender engines.
The underlying assumption of this approach is that if Item 1 and Item 3 are considered similar as they are positively rated by both User 1 and User 2. Thus, Item 1 can be recommended to User 3 as it already shows interest in Item 3.
<a id="Context"></a>
## Context

The datasets describe ratings and free-text tagging activities from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users had rated at least 20 movies.
<a id="Business_Problem"></a>
## Business Problem

Developing a recommendation system based on similarly rated films.
<a id="Attribute_Information"></a>
## Attribute Information

The two files from the data will be used in this study as rating.csv and movie.csv

rating.csv that contains ratings of movies by users:

* userId
* movieId
* rating

timestamp movie.csv that contains movie information:

* movieId
* title
* genres
<a id="Task_Details"></a>
# Task Details

**Step 1:** Preparing the Data Set  
**Step 2:** Creating User Movie Df  
**Step 3:** Making Item-Based Movie Suggestions



