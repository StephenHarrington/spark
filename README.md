# spark
Apache Spark

This repo contains Jupyter python notebooks demonstrating the use of the pySpark and MLlib modules explored in solving machine learning problems in Berkeley courses CS100.1 and CS190.1 as hosted on the edX platform.

CS100.1 : Introduction to Big Data with Apache Spark

lab1 : Word count
This lab will build on the techniques covered in the Spark tutorial to develop a simple word count application.  The volume of unstructured text in existence is growing dramatically, and Spark is an excellent tool for analyzing this type of data.  In this lab, we will write code that calculates the most common words in the [Complete Works of William Shakespeare](http://www.gutenberg.org/ebooks/100) retrieved from [Project Gutenberg](http://www.gutenberg.org/wiki/Main_Page).  This could also be scaled to find the most common words on the Internet.


lab2 : Server log analysis
Server log analysis is an ideal use case for Spark.  It's a very large, common data source and contains a rich set of information.  Spark allows you to store your logs in files on disk cheaply, while still providing a quick and simple way to perform data analysis on them.  This homework will show you how to use Apache Spark on real-world text-based production logs and fully harness the power of that data.  Log data comes from many sources, such as web, file, and compute servers, application logs, user-generated content,  and can be used for monitoring servers, improving business and customer intelligence, building recommendation systems, fraud detection, and much more.


lab3 : Entity Resolution
Entity Resolution (ER) refers to the task of finding records in a dataset that refer to the same entity across different data sources (e.g., data files, books, websites, databases). ER is necessary when joining datasets based on entities that may or may not share a common identifier (e.g., database key, URI, National identification number), as may be the case due to differences in record shape, storage location, and/or curator style or preference. A dataset that has undergone ER may be referred to as being cross-linked.

lab4 : Movie Recommender System
One of the most common uses of big data is to predict what users want.  This allows Google to show you relevant ads, Amazon to recommend relevant products, and Netflix to recommend movies that you might like.  This lab will demonstrate how we can use Apache Spark to recommend movies to a user.  We will start with some basic techniques, and then use the [Spark MLlib][mllib] library's Alternating Least Squares method to make more sophisticated predictions.

CS190.1 : Scalable Machine Learning
NOTEBOOKS NOT SHOWN UNTIL AFTER COURSE ENDS

lab1 : Math and Python Review
This notebook reviews vector and matrix math, the [NumPy](http://www.numpy.org/) Python package, and Python lambda expressions.  It also covers downloading the data required for Lab 4, where you will analyze website click-through rates.  Part 1 covers vector and matrix math, and you'll do a few exercises by hand.  In Part 2, you'll learn about NumPy and use `ndarray` objects to solve the math exercises.   Part 3 provides additional information about NumPy and how it relates to array usage in Spark's [MLlib](https://spark.apache.org/mllib/).  Part 4 provides an overview of lambda expressions, and you'll wrap up by downloading the dataset for Lab 4.

lab3 : Linear Regression 
 This lab covers a common supervised learning pipeline, using a subset of the [Million Song Dataset](http://labrosa.ee.columbia.edu/millionsong/) from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/YearPredictionMSD). Our goal is to train a linear regression model to predict the release year of a song given a set of audio features.
 
 lab4 : CTR Prediction
 This lab covers the steps for creating a click-through rate (CTR) prediction pipeline.  You will work with the [Criteo Labs](http://labs.criteo.com/) dataset that was used for a recent [Kaggle competition](https://www.kaggle.com/c/criteo-display-ad-challenge).
