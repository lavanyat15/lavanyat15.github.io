---
title: "Project 2 - Customer Brand Preference Analysis / Market Basket Analysis"
date: 2021-04-29
tags: [data analytics, data science, classification, regression]
header:
image: "/images/perceptron/percept.jpg"
excerpt: "Regression and Classification Modeling in R using RStudio"
mathjax: "true"
---

# Overview
There are 2 parts to this course 
1. Used machine learning methods to predict which brand of computer products customers prefer, based on customer demographics collected from a marketing survey . [T2, T3]
 
2. Determine associations between products that will be used to drive sales-oriented initiatives such as recommender systems. [T4]

[T1 : Intro to R ](https://github.com/lavanyat15/DataScience-Code/tree/main/(C3)Predicting%20customer%20Pref%20in%20R/(T1)%20Intro%20to%20R)

Goals : 

To learn R by analysing and bugfixing. 
This is a tutorial based task to learn the basics of analytics and visualization using R. 
Within the tutorial, worked through a regression analysis using a linear regression model by  predicting distances through the speed of certain cars. 
The dataset used is the cars.csv file.

Since the best way to learn is through trial and error, so after cars.csv, worked by running a script of code. 
The dataset is the iris.csv file, and the task was to debug errors in the script.

[T2 - Predict Customer Brand Preference for Blackwell Electronics ](https://github.com/lavanyat15/DataScience-Code/tree/main/(C3)Predicting%20customer%20Pref%20in%20R/(T2)%20Predict%20CustomerBrandPref)

Analysis goals :

To build a model to predict responses on incomplete dataset about which product sells more based on a complete responses from customers. 

The sales team engaged a market research firm to conduct a survey of existing customers. 
One of the objectives of the survey was to find out which of two brands of computers our customers prefer. Unfortunately, the answer to the brand preference question was not properly captured for all of the respondents.

To do this, optimized two different decision tree classification methods in R - C5.0 and RandomForest - and compare which one works better for this data set. 
Data file labelled CompleteResponses.csv is the data set to train your model and build your predictive model. It includes ~10,000 fully-answered surveys and the key to the survey can be found in survey_key.csv. 
The file labelled SurveyIncomplete.csv is test set (the data you will apply your optimized model to predict the brand preference). 
You'll be applying your trained and tested model to this data to prepare the model for production.

[T3 - Multiple Regression in R](https://github.com/lavanyat15/DataScience-Code/tree/main/(C3)Predicting%20customer%20Pref%20in%20R/(T3)Multiple%20Regression%20R)

Analysis goals :

Predicting sales of four different product types: PC, Laptops, Netbooks and Smartphones
Assessing the impact service reviews and customer reviews have on sales of different product types.

```
Tools: R, R Studio, Caret, ggplot2
Models : GBM, Random Forest, C5.0, SVM, XGBoost

```
