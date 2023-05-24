# Starbucks Capstone
Capstone Project for Udacity Data Scientist Course

##Introduction
The data provided is set to mimic a customers behavior and purchasing habits on the Starbucks mobile app. For context Starbucks sends out regular offers to users of the app. The offer varies from ads, discounts, or buy one get one free deals. Not all users receive offers every week and not all users receive the same offers. This blog post is aimed at a technical audiance but I will do my best to describe the process as simply as possible.

My goal was to combine the data given and predict whether or not a customer was likely to spend $10 or more at Starbucks based on the offer received. To do this I pulled in age, gender, and the avenue the offer was provided through (web, mobile, social , email).

##Libraries required
Before running the script you must have the following libraries installed
pandas
numpy
math
json
matplotlib
sklearn
seaborn
tensorflow

##Project and file structure
The structure for this project is relativly simple. There is one jupyter notebook titled Starbucks_Capstone_notebook.ipynb that contains all the code for the project.
There is also a data folder that contains 3 .json files
portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed

