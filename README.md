# Body-Growth-Model
Code for a modeling body growth using a quadratic log-log model.

# Project/Code Objective
This code was developed for a project that was looking at the effects of environmental influencers of bone growth, such as rainfall, temperature, etc., in one species.  

However, because bones/the skeletal system is a highly dynamic tissue that is sensitive to ontogeny, phylogeny, biomechanical, and environmental factors (de Ricqlès, 1993), we had to control for each factor we are not studying (i.e., ontogeny, phylogeny, and biomechanics), to identify and study the environmental factors/influencers on bone growth. 

Because of the nature of the sample (looking at one species), we were able to control for the phylogenic factor. We were also able to control for the biomechanical factors by looking at one bone at a time. 

Which left ontogeny that we needed to control for to identify the effects of environment on bone growth. 

To consider changes in body size with age during development, or growth, this code models the response variable (in this case bone length) as a function of age, using a quadratic log-log model.

The quadratic log-log model log transforms both age and the response variable. 

We have to model bone growth (or body size growth) as a quadratic formula because while bones/body size does increase with age it is not a linear growth or a continuous growth, but at some point in time the growth plateaus and even decreases with age (i.e., at elderly ages). 

# Code breakdown 

This code includes:
1. Function to filter the data frame to the information that is required. 
2. Calculates means, min, and max of the response variable, by sex and age group.
3. Functions to visualizes the log-log model, by combined sex and separated sex.
4. Functions for a loess plot, by combined sex and separated sex. 

# About data set
The data set provided to conducted the analysis is simulated data based on real existing data sets to explore skeletal growth patterns. The simulated data closely resembled actual data in terms of distribution and characteristics, allowing for comprehensive analysis and insights. This approach facilitated the exploration of various scenarios and provided valuable insights for decision-making and planning
