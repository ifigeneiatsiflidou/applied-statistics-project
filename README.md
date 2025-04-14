# Applied Statistics Project 
This project was created as part of an **Applied Statistics** course and focuses on analyzing and predicting the worldwide box office revenue of movies using statistical techniques and data analysis in Python.

## Project Overview
The dataset includes 3,000 movies from **The Movie Database (TMDb)**, featuring details like: budget, popularity, language, cast, and production companies. The project is divided into 2 exercises:

## Exercises
### Exercise 1: Exploratory Analysis and Feature Selection Based on Correlation

We begin by analyzing the relationship between the revenue and four explanatory variables:
-	budget
-	english (a binary variable indicating whether the original language is English)
-	runtime
-	popularity

For each numerical explanatory variable, we compute the correlation coefficient with revenue and visualize the relationships using scatter plots. 
Based on the correlation values and visual evidence, we determine which single variable is the most informative for predicting movie revenue.

### Exercise 2: Multiple Linear Regression

We extend our analysis by exploring additional variables that may improve our ability to predict movie revenue.
Most of the dataset’s remaining information is in text or JSON format. From this, we engineer two new numerical explanatory variables:	
-	The number of male cast members per movie (from the cast field)
-	The number of production companies involved in each movie (from the production_companies field)

We then:
-	Calculate the correlation of these new variables with revenue
-	Select the four most predictive features (budget, popularity, men, companies)
-	Fit a multiple linear regression model using scikit-learn
-	Evaluate the model using the R² score and a histogram of residuals
-	Interpret the model coefficients and discuss variable importance

The goal is to understand which variables most strongly affect movie revenue and how well a linear model can explain the variability in the data.

## Contents
`movie_revenues.csv` : Dataset with 3,000 movies 

`Applied_statistics_project.ipynb` : Main Jupyter notebook with code and analysis 

`Applied-Statistics-Project.pdf`: Final report


