# Body-Growth-Model
Code for a modeling body growth using a quadratic log-log model 

To consider changes in size with age during development, or growth, this code models a response variable (in this case bone length) as a function of age, using a
quadratic log-log model.

The quadratic log-log model log transforms both age—log(age) and log(age^2)—and the response variable. 

This code also includes:
  - Function to filter the data frame to the information that is required. 
  - Functions to visualizes the log-log model, by combined sex and separated sex.
  - Functions for a loess plot, by combined sex and separated sex. 
