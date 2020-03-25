# Nieves Response

Random Forest modeling is a nonparametic, nonlinear machine learning alogrithm that distributes a larger data set accross subsets using covariate data sets. The RF model creates a node from the original piece of data and then grows the decision tree using covariate data sets to distribute the original data. The RF model uses bagging to automatically decide which covariates are most important at each node and distribute the data based on that. This bagging method creates an importance score, allowing the user to see which covariates are the best predictors. 

The RF model in this paper is predicting population density across gridcells, and then it uses dasymetric population allocation (this assigns each gridcell a proportion of a whole) to distibute actual population counts on the basis of the density weighting layer. This paper is trying to find which covariates are most imoprtant when understanding the drivers of population location (for example, how important are water sources in where people chose the settle). This paper found that the most imoprtant covariates are urban/suburban extents, built environment and urban/suburban proxies, climatic/environmental variables, populated place covariates, and transportation networks.


