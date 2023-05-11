# Body-Growth-Model
Code for a modeling body growth using a quadratic log-log model.

# Project/Code Objective
This code was developed for a project that was looking at the effects of environmental influencers of bone growth, such as rainfall, temperature, etc., in one species.  

However, because bones/the skeletal system is a highly dynamic tissue that is sensitive to ontogeny, phylogeny, biomechanical, and environmental factors (Fig 1), we had to control for each factor we are not studying (i.e., ontogeny, phylogeny, and biomechanics), to identify and study the environmental factors/influencers. 

Because of the nature of the sample (looking at one species), we were able to control for the phylogenic factor. We were also able to control for the biomechanical factors by looking at one bone at a time. 

Which left ontogeny that we needed to control for to identify the effects of environment on bone growth. 

To consider changes in body size with age during development, or growth, this code models a response variable (in this case bone length) as a function of age, using a quadratic log-log model.

The quadratic log-log model log transforms both age — log(age) and log(age^2) — and the response variable. 



# Code breakdown 

This code also includes:
1. Function to filter the data frame to the information that is required. 
2. Calculates means, min, and max of the response variable, by sex and age group.
3. Functions to visualizes the log-log model, by combined sex and separated sex.
4. Functions for a loess plot, by combined sex and separated sex. 
