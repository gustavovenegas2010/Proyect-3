# Recommendations-with-IBM

## 1. Project Motivation

This project is part of the second project of the data science course at Udacity. The goal is to analyze user interactions with articles on the IBM Watson Studio platform, and make recommendations for new articles that may be to their liking.

## 2. File Description

The Jupyter Notebook includes the following steps

* Exploratory Data Analysis Before making recommendations of any kind, I explore the data I am working with for the project.

* Rank Based Recommendations To get started in building recommendations, I first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles I might recommend to new users (or anyone depending on what we know about them).

* User-User Based Collaborative Filtering In order to build better recommendations for the users of IBM's platform, I could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

* Matrix Factorization Build use matrix factorization to make article recommendations to the users on the IBM Watson Studio platform

## 3. Instructions
Ejecute los siguientes comandos en el Python 3.

## 4. Author and Acknowledgements
The author of this project is Gustavo Venegas Segura, Statistician with a specialization in statistics from the National University of Colombia, currently working at Banco Davivienda. Special thanks to Jorge Andrés Escobar and Udacity for their help in this project.
