# Movie Recommender User Based Filtering Application

## Table of contents
* [Introduction](#Introduction)
* [Context](#Context)
* [Business Problem](#Business_Problem)
* [Attribute Information](#Attribute_Information)
* [Task Details](#Task_Details)

![image](https://user-images.githubusercontent.com/83332641/161727509-52f78a7c-4e87-41a6-994f-c93648983b5e.png)

## Introduction
You have left behind a very tiring day and now you want to watch a good movie. This time period that you want to spend with pleasure can be challenging with the abundance of movie options. We are lucky that recommender systems exist for this.

A user-based collaborative filtering recommendation system for preferences in movie selection could make predictions about which movie a user should like given a partial list of that user's tastes.

User-based collaborative filtering is a method of making predictions about the interests of a user by collecting preferences of many other users. The underlying assumption of this approach is that if a User-1 has the same opinion as a User-3 on an issue, User-1 is more likely to have User-3's opinion on a different issue than that of a randomly chosen person.


## Context

The datasets describe ratings and free-text tagging activities from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users had rated at least 20 movies.

## Business Problem

Make a movie recommendation using the user-based recommender method for the user whose ID is given.

## Attribute Information

The two files from the data will be used in this study as rating.csv and movie.csv

rating.csv that contains ratings of movies by users:

* userId
* movieId
* rating
* timestamp

movie.csv that contains movie information:

* movieId
* title
* genres

## Task Details

**Step 1:** Preparing the Data Set
**Step 2:** Determining the Movies Watched by the User to Suggest  
**Step 3:** Accessing Data and Ids of Other Users Watching Same Movies  
**Step 4:** Identifying Users with the Most Similar Behaviors to the User to Suggest  
**Step 5:** Calculating the Weighted Average Recommendation Score  
