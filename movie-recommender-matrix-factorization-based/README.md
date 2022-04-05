# Matrix Factorization Based Movie Recommender

## Table of contents
* [Introduction](#Introduction)
* [Context](#Context)
* [Business Problem](#Business_Problem)
* [Attribute Information](#Attribute_Information)
* [Task Details](#Task_Details)

![image](https://user-images.githubusercontent.com/83332641/161723810-4cad7acf-7ad4-4cc0-8248-be69a179b577.png)


## Introduction

Matrix factorization is a class of collaborative filtering algorithms used in recommender systems. Matrix factorization algorithms work by decomposing the user-item interaction matrix into the product of two lower dimensionality rectangular matrices.The idea behind matrix factorization is to represent users and items in a lower dimensional latent space. For the case here, the items represent movies

Our aim is to fill in the blank rating values here. For users and movies to populate them, the weights of the latent features, that are supposed to be available, are found from the available data. Then, with these weights, an estimate is made for the empty rating values.


## Context

The datasets describe ratings and free-text tagging activities from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users had rated at least 20 movies.

## Business Problem

Developing a recommendation system that gives estimated ratings for a given user and movie, based on on single value decomposition by using Surprise Library.

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

**Step 2:** Modeling

**Step 3:** Model Tuning

**Step 4:** Final Model and Prediction
